---
title: Generative AI and its Consequences
date: 2025-06-17
tags: AI
---


![]({{ "/img/shodan.png" | relative_url }})

Some technologies can be harmful to humanity. 

Artificial Intelligence certainly has the potential to be one of them. The bright side is that ultimately we are the ones developing it, and can hopefully make the right decisions along the way. For that to happen, we need to educate ourselves, engage in healthy discussions about the consequences of this technology, remain critical, and not fall for the hype of the cherry-picked benchmarks. My hope is that this article will provide you with enough context to empower you to formulate your own thoughts about the topic with more clarity than before.

## What led us here?

It is important to understand the context of how we ended up in this situation. AI is currently experiencing the biggest wave of hype and investment that it has ever seen. It has become accessible and mainstream... but where did it come from?

Let me begin my discussing the concept of information transmission. Sharing information is an inherently human thing to do. It is, after all, what creates connections between us and brings us together. Throughout history there have been multiple 'paradigm shifts' in how information can spread. Cave paintings and pictograms. The invention of alphabets and languages. The printing press. Radio and television. The rise of computers - which led to the mass digitalization of documents, the creation of the Internet, and eventually of social media.

The trend is clear. Over time we have developed newer and better ways to more easily spread information to an ever-increasing range of people. This is inherently a brilliant achievement. Now, more people than ever have access to near-infinite amounts of information.

The natural consequence of these developments, and particularly the digital age, is the exponential rise in the quantity of available data. Not only that, analytics are king. Everything is monitored, tracked and measured. This (among many more reasons) results in what is known as Big Data - large and diverse datasets which rapidly grow over time. These datasets create their own unique problems - namely storage and processing. The answers to these problems? The advancements of the Cloud and High Performance Computing.

More data, coupled with the ability to process it, meant that AI was a natural progression given the state of the world. This brings us to where we are today - with tremendous amounts of investment and ongoing research into the world of AI. We are amidst a rat race, where everyone wants to have the 'most intelligent' model capable of outperforming the competition. AI is the current hot trend, but in reality Artificial Intelligence is not a new concept. I think it is important to acknowledge that, and to recognize the giants whose shoulders we stand on today.

### A Brief History of AI

All the way back in 1950 Alan Turing published his paper '[Computing Machinery and Intelligence][turing-computing]'. In it he posed the question - "Can a machine exhibit intelligent behaviour indistinguishable from that of a human?". This paper can largely be attributed to the birth of interest in the field of AI. It sparked a plethora of research and resulted in lots of advancements in the following decades; many of which are still relevant today.

- 1951 - The first neural network was built. 
- 1955 - The phrase 'artificial intelligence' was coined. 
- 1965 - ELIZA was developed - known as the first 'intelligent' chatbot.
- 1969 - The concept of backpropagation was first introduced.

The 1970s, however, were not quite as promising. They brought on the first major "AI Winter" - a period of decreased funding and interest in AI research. This is largely accredited to the ['Lighthill report][lighthill-report]' which claimed that the field had not produced the significant breakthroughs which were promised. This led to a loss of support from companies and governments.

Although the excitement and funding returned in the 1980s, it did not stay for long. In 1984 at an annual meeting of the Association for the Advancement of Intelligence (AAAI) the world was cautioned of another impending AI Winter (in fact this is where this phrase was coined). It was predicted that history was going to repeat itself, and as in the 1970s, investment and research would collapse due to inflated expectations and underwhelming results. Within just three years this became reality and the second AI Winter had arrived.

A pattern was emerging - an initial wave of hype and excitement, which in turn led to disillusionment and overblown expectations, which could not be met, and thus disappointment. As we reflect on where we are today, we must keep the past in mind and ride the wave of excitement with cynicism at heart, as to not repeat the same mistakes.

Nonetheless, the cycle of research continued and throughout the next decades many more significant advancements occurred, particularly after we entered the 21st century. Some of these are:

- 1988 - Rollo Carpenter developed the Jabberwacky chatbot which learned from human interactions, rather than being rule based.
- 1989 - Handwritten ZIP code images were recognized by a Convolutional Neural Network at Bell Labs.
- 1997 - Deep Blue beat Kasparov at chess.
- 2009 - Andrew Ng et al. published "Large-scale Deep Unsupervised Learning using Graphics Processors" which recognised the advantage of GPUs for AI workloads.
- 2011 - Apple launched Siri.
- 2012 - Andrew Ng and Jeff Dean trained a neural network on YouTube videos which learnd to recognise images of cats.
- 2016 - AlphaGo beat Lee Sedol at Go.
- 2017 - Facebook's chatbots developed their own language in communication between each other.

This brings us to the modern day, where AI is once again at the top of everyone's minds, and many believe that we are in the middle of an AI Spring - but what exactly happened between 2017 and 2025?

### The Transformer Goes Boom

Despite what the name of this section might suggest, this section does not discuss the movie franchise directed by Michael Bay. Instead the focus will be on the transformer model architecture, and it's significance in the context of today's AI models. Before we get to transformers though, we first need to talk about LLMs.

Large Language Models (LLMs) are a type of machine learning model designed for natural language processing tasks - i.e. they can "understand" and generate human language via deep neural networks. The "Large" in LLM comes from the amount of training data which is used to provide its foundational capabilities, as well as the amount of parameters used - which is often used to describe the size of the model. Essentially, the larger the model, the more information it can learn during training, which in turn makes its predictions more accurate. This is also part of why it is so expensive to train good models - larger models mean more data, which means more storage and compute, which means higher cost.

The idea of a model which can understand natural language and interact with a human has been around for decades - as noted above with ELIZA, Jabberwacky and many others which came along the way. However, there has been a recent revolution in the space with the arrival of the transformer architecture in 2017, introduced in the paper - [Attention Is All You Need][transformer-paper], by Ashish Vaswani et al.

The transformer model is a type of neural network architecture based on *attention* - hence the title of the paper. This in essence allows the model to determine and focus on what is most important about a specific sequence of data. For example, it could understand words within a context or assess a words significance within a sentence. Transformers do not process words sequentially one at a time, but instead, process the entire input all at once.

One of the first majorly successful applications of transformers was BERT - Bidirectional Encoder Representations from Transformers - introduced by Google in 2019 - which could predict or classify input text. The model quickly became ubiquitous, and is still used today as the basis of Google search. Despite its fame though, BERT was soon overtaken in popularity by OpenAI's GPT models. GPT stands for Generative Pre-trained Transformer, which can be broken down as follows:

- Generative Pre-training is the ability to train language models with unlabeled data and apply those patterns to new inputs. GPTs _generate_ new data by applying the patterns and structure of their _pretraining_ data to user inputs.
- Transformer models are a type of neural network specialised in Natural Language Processing. They can process the entire input sequence in parallel and identify the importance of words.

With the release of ChatGPT in 2022, the general public was introduced into a new era of Generative AI, which has taken the world by storm. AI has never been so mainstream and accessible before. This begs the question - are we ready for it?

## What's different now?

Earlier I touched on the different technological paradigm shifts which have impacted how we share information with each other - radio, television and the Internet. Artificial Intelligence certainly fits the bill to be included on this list, but it largely stands out from the rest. Unlike all the others, AI is not a medium for humans to communicate.

Historically information has always travelled from one human to another - for example, a radio show host talking to their audience, or a printed document sent to an executive. Regardless of whether or not technology was involved in between, the nodes of the information network graph have always been humans. We are the ones who decide what to write, who to send it to and how to send it to them. The technology merely acts as the connecting edge.

![](/img/info-network.png)

With the emergence of AI, a non-human node is introduced into the network for the first time in history. To examine why AI classifies as a node and not simply an edge, lets compare it to the radio. The radio by itself cannot create any information, nor can it decide on who should receive it. It cannot make decisions. The radio requires a human presence to be useful. On the other hand, an AI system may generate a political news article by itself and publish it to the web. Another AI system may detect this article and make a decision about it - for example marking it as spam, or reposting it, depending on how it perceives the content. A third system may observe this reaction, and take corresponding action by selling risky stocks and buying government bonds instead. Other systems who may be observing the market could notice this and follow suit themselves. This could all take place within a matter of seconds, without any human intervention, and quite likely even without their awareness. This is the difference. AI can generate content and make decisions by itself, which makes it a fully fledged member of the information network.

![](/img/info-network-computer.png)

At the moment, we still play a crucial role in this network, but this may change. As AI becomes more "intelligent" we will likely be pushed out, and information networks without any human members could very well emerge. We really need to think about the consequences that this may have. Importantly, as the models get larger in size, consume more data, and their algorithms grow in complexity, the decision making frameworks will become incomprehensible to humans - that is, if they are not already. We will thus lose the ability to understand how the algorithms reached certain conclusions, allowing them control our lives without comprehension. It should go without saying this has the potential to become very concerning if not regulated accordingly.

Nonetheless, it is the humans who are developing this next wave of technology (at least for now). It is our responsibility to understand what we can do to leverage our agency, and how to best continue in the right direction. At the end of the day, a technology is not inherently evil** - that is decided by how it is used. For example, during the Second World War the radio was used to spread news and uplift citizens in certain parts of the world, and to spread propaganda of totalitarian regimes in others. The technology was the same in both cases, but how it was utilized was what made all the difference. 

There is also a danger that we will divide the world's information networks ourselves, as a result of the AI arms race. The whole world is rarely ever exclusively in agreement on anything, and AI will be no exception. Different governments and organizations around the world will likely push for their own technologies and algorithms, and be opinionated about how they are used and regulated. They may also begin to take more responsibility and ownership over their data, tightly controlling who can access it and use it for training. For example, it may be in China's best interest to not allow the United States to access any of the data or algorithms which were used for training their newest models (and vice-versa). This conflict of interest becomes all the more apparent when one considers the potential of AI within military or government applications. Once the first domino falls, the outcome might not be reversible. What we currently know as the World Wide Web, may soon become a set of disjointed cocoons.

** See 'The Alignment Problem'

---

To be continued...

<!-- ## References -->

[turing-computing]:https://www.csee.umbc.edu/courses/471/papers/turing.pdf
[lighthill-report]:https://rodsmith.nz/wp-content/uploads/Lighthill_1973_Report.pdf
[transformer-paper]: https://arxiv.org/abs/1706.03762