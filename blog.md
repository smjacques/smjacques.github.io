---
layout: default
title: Blog
weight: 5
---

<ul>
{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
  {{ post.excerpt }}
  </li>
{% endfor %}
</ul>