---
layout: default
title:  "Pedagogy"
categories: [Pedagogy]
---

<ul>
  {% for post in site.categories.Pedagogy %}
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
    <span>{{ post.date | date_to_string }}</span>
     <span style="font-size: 1.3em"> {{ post.excerpt }}</span>
 
  {% endfor %}
</ul>

---
