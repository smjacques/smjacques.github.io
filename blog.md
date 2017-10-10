---
layout: default
title: Blog
weight: 4
---

{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; <h3 style="color:#424242;"> [ {{ post.title }} ]<({{ post.url }})</h3>
{% endfor %}
