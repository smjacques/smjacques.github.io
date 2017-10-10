---
layout: default
title: Blog
weight: 4
---

{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}" style="color:#616161;" style"text-transform: capitalize;">{{ post.title }}</a></li>
{% endfor %}


