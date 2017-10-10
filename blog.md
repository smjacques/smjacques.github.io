---
layout: default
title: Blog
weight: 4
---

{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <h3 style="color:#424242;" href="{{ post.url }}">{{ post.title }}</h3></li>
{% endfor %}


