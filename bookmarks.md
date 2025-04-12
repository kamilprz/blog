---
layout: page
title: Bookmarks
description: Tools and resources
---

A collection of tools, papers, cheatsheets and other resources which I like.

{% for category in site.data.bookmarks %}
{% assign items = category[1] | sort_natural: "name" %}
### {{ category[0] | capitalize }}
{% for item in items %}
* [{{ item.name }}]({{ item.link }}){:target="_blank"}
  * {{ item.description }}
{% endfor %}
{% endfor %}
