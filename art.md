---
layout: default
title:  "Art"
date:   2020-04-24 20:03:11
categories: [Art]
---


<!--{% for post in site.categories.Art %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}-->

<ul>
 {% for post in site.categories.Art %}
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
    <span> Posted on {{ site.time | date_to_long_string }}</span>
    <span style="font-size: 1.3em">  {{ post.excerpt }}</span>
  
  {% endfor %}
</ul>

---