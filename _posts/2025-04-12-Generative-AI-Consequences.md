---
title: Generative AI and its Consequences
date: 2025-04-12
tags: AI
---

Some technologies can be harmful to humanity. 

Generative AI certainly seems to be heading in that direction. The bright side is that ultimately we are in control of how things play out, and can hopefully make the right decisions along the way. For that, I think we need to engage in healthy discussions about the consequences of this technology and not blindly jump on board the hype train, fascinating over the latest cherry-picked benchmarks.

The more time that I spent thinking about this topic, the more it became apparent to me that writing this blog will not be possible without also talking about the state of the Internet and its implications for our society. This will be a prevalent theme throughout many of the sections.

## What led us here?

Sharing information is an inherently human thing to do. It is, after all, what creates connections between us and brings us together. Throughout history there have been multiple 'paradigm shifts' in how information can spread. Cave paintings and pictograms. The invention of alphabets and languages. The printing press. Radio and television. The rise of computers - which led to the mass digitalization of documents, the creation of the Internet, and eventually of social media.

The trend is clear. Over time we have developed newer and better ways to more easily spread information to an ever-increasing range of people. This is inherently a brilliant achievement. Now, more people than ever have access to near-infinite amounts of information. 

The natural consequence of these developments, and particularly the digital age, is the exponential rise in the quantity of available data. It is now easier than ever to create something (I'm not referring to Generative AI yet!) and post it online for the world to see. Not only that, analytics are king. Everything is monitored, tracked and measured. This (among many more reasons) results in what is known as Big Data - large and diverse datasets which rapidly grow over time. These datasets create their own unique problems - namely storage and processing. The answers to these problems? The advancements of the Cloud and High Performance Computing.

More data, coupled with the ability to process it, meant that AI was a natural progression given the state of the world. This brings us to where we are today - with lots of investment and ongoing research into the world of AI, and a rat race where everyone wants to create the next best model. It is the hot new buzz-word which is shoehorned into every advertisement and product. In reality though, Artificial Intelligence is not a new concept, and I think it is important to acknowledge that and recognise the efforts that have led us to this point in time.  

### A Brief History of AI

All the way back in 1950 Alan Turing published his paper '[Computing Machinery and Intelligence][turing-computing]'. In it he posed the question - "Can a machine exhibit intelligent behaviour indistinguishable from that of a human?". This paper can largely be attributed to the birth of interest in the field, and resulted in many advancements in the following decades.

- 1951 - The first neural network is built. 
- 1955 - The phrase 'artificial intelligence' is coined. 
- 1965 - ELIZA is developed - known as the first 'intelligent' chatbot.
- 1969 - The concept of backpropagation is first introduced.

Even this early on we see many significant breakthroughs which are still relevant today. 

However, the 1970s were not quite as promising. They brought on the first major AI Winter - a period of decreased funding and interest in AI research. This is largely accredited to the ['Lighthill report][lighthill-report]' which claimed that the field had not produced the significant breakthroughs which were promised, and this led to a loss of support from companies and governments.

Although the excitement and funding returned in the 1980s, it did not stay for long. In 1984 at an annual meeting of the Association for the Advancement of Intelligence (AAAI) the world was cautioned of another impending AI Winter (in fact this is where this phrase originates from). It was predicted that history was going to repeat itself, and as in the 1970s, investment and research would collapse due to inflated expectations and underwhelming results. Within just three years this became reality and the second AI Winter had arrived.

The pattern is there - a wave of hype and excitement, leading to disillusionment - which results in the failure to meet the overblown expectations and thus disappointment. As we move forward, we must ride the wave with cynicism in mind and learn to temper our expectations.

Nonetheless, throughout the next decades, many significant advancements still occur. Some of these are:

- 1988 - Rollo Carpenter develops the Jabberwacky chatbot which learns from human interactions, rather than being rule based.
- 1989 - Handwritten ZIP code images are recognized by a Convolutional Neural Network at Bell Labs.
- 1997 - Deep Blue beats Kasparov at chess.
- 2009 - Andrew Ng et al. publish "Large-scale Deep Unsupervised Learning using Graphics Processors" which recognises the advantage of GPUs for AI workloads.
- 2011 - Apple launches Siri.
- 2012 - Andrew Ng and Jeff Dean train a neural network on YouTube videos which learns to recognise images of cats.
- 2016 - AlphaGo beats Lee Sedol at Go.
- 2017 - Facebook's chatbots develop their own language in communication between each other.

This brings us to the modern day, where AI is once again at the top of everyone's minds.

### The Transformer Boom

Despite what the name of this section might suggest, I will not be talking about the movie franchise directed by Michael Bay. Instead the focus will be on the transformer model architecture and it's significance in the modern day. Before we can get there though, we first need to talk about LLMs.

Large Language Models (LLMs) are a type of machine learning model designed for natural language processing tasks - i.e. they can "understand" and generate human language via deep neural networks. The "Large" in LLM comes from the amount of training data which is used to provide its foundational capabilities, alongside the amount of parameters present - which is often used to describe the size of the model. Essentially, the larger the model, the more information it can learn during training, which in turn makes its predictions more accurate. This is also part of why it is so expensive to train good models.

The idea of a model which can understand natural language and interact with a human has been around for decades - as noted above with ELIZA, Jabberwacky and many others which came along the way. However, there has been a recent revolution in the space with the arrival of the transformer architecture in 2017, introduced in the paper - [Attention Is All You Need][transformer-paper], by Ashish Vaswani et al.

The transformer model is a type of neural network architecture based on *attention* - hence the title of the paper. This in essence allows the model to determine, and focus on what is most important about a specific sequence of data. For example it could understand words within a context, or assess their importance. Transformers also do not process words sequentially one at a time, but instead, process the entire input all at once.

One of the majorly successful applications of transformers was BERT - Bidirectional Encoder Representations from Transformers - introduced by Google in 2019, which could predict or classify input text. The model quickly became ubiquitous, and is still used today as the basis of Google search. Despite its fame though, BERT was soon overtaken in popularity by OpenAI's GPT models. GPT stands for Generative Pre-trained Transformer, which can be broken down as follows:

- Generative Pre-training is the ability to train language models with unlabelled data and apply those patterns to new inputs. GPTs _generate_ new data by applying the patterns and structure of their _pretraining_ data to user inputs.
- Transformer models are a type of neural network specialised in Natural Language Processing. They can process the entire input sequence in parallel and identify the importance of words.

With the release of ChatGPT in 2022, the general public was introduced into a new era of Generative AI. Let's see where it will take us.

## What's different now?

Earlier I touched on the different technological paradigm shifts which impacted how we share information with each other - radio, television and the Internet. Artificial Intelligence certainly fits the bill to be included on this list, but it largely stands out from the rest - let me explain why.

Unlike all the others on the list, AI is not a medium for humans to communicate. Previously information always travelled from one human to another - for example, a radio show host or a news anchor on the TV talking to their audience. AI on the other hand, doesn't require human participation. A learning algorithm can scrape information from the Internet, or a data warehouse, and come to informed decisions on its own - for example to recommend you a certain post on your feed. This is the first time in history where humans are cut from the information network. We really need to think about the consequences that this may have. Importantly, as the models get larger in size, consume more data, and their algorithms grow in complexity - the decision making frameworks become incomprehensible to humans, and we lose the ability to understand how the algorithms reached certain conclusions. Naturally, this has the potential to become very concerning if not regulated accordingly.

In the case of Generative AI, it is the first time in history where the medium can create content by itself. A book always needed to be written by an author, a TV show needed to have actors and directors. However, tools such as ChatGPT can now independently generate text, DALL-E can generate images, Sora can generate video - all based on a simple input prompt. This of course has its own implications for the state of the Internet - a topic which will be discussed in further detail in later sections. In short, the web is being polluted at a steadily increasing pace, and is in danger of becoming a ghost-town, mainly populated by AI bots creating content for no-one to see.

Nonetheless, it is the humans who are developing this next wave of technology (at least for now). This means that we need to understand what we can do to leverage our agency, and how to continue in the right direction. At the end of the day, a technology is not inherently evil - it is about how it is used. Take the example of the radio during the Second World War. It was used to spread news and uplift citizens in certain parts of the world, and to spread propaganda of totalitarian regimes in others. The technology was the same in both cases, but how it was utilized was what made all the difference. 

The danger here is that the progression of AI will likely create a divide - the whole world is rarely ever exclusively in agreement on anything, and AI will be no exception. What this means is that different governments and organisations around the world will push for their own technologies and algorithms, and be opinionated about how they are used and regulated. It is very likely that this will lead to conflict. What we currently know as the World Wide Web, might soon become a set of disjointed cocoons.

---

To be continued...

<!-- ## References -->

[turing-computing]:https://www.csee.umbc.edu/courses/471/papers/turing.pdf
[lighthill-report]:https://rodsmith.nz/wp-content/uploads/Lighthill_1973_Report.pdf
[transformer-paper]: https://arxiv.org/abs/1706.03762