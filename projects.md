---
layout: default
title:  "Projects"
date:   2020-04-24 20:03:11
categories: [Projects]
---


{% for post in site.categories.Projects %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

---