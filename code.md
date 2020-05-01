---
layout: default
title:  "Code Snippet Samples"
date:   2020-04-24 20:03:11
categories: [Code]
---


{% for post in site.categories.Code %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

---