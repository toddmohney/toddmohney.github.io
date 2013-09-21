---
layout: default
title: Amazing Homepage
---

This is an amazing homepage

Here's all the cool posts so far:

{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})
{% endfor %}

Here's an [about]({{ site.url }}/about) page: 
