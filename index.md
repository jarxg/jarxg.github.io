---
title: index
layout: default
---

# Texts

[Lecture on Nothing](txt/nothing.html)

# Blog posts

{% for post in site.posts %}
  [{{ post.date | date_to_string }} - {{ post.title }}]({{ post.url }})
{% endfor %}
