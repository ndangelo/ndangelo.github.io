---
layout: default
title:  "Art"
categories: [Art]
---



 {% for post in site.categories.Art %}
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
   <span>{{ post.time | date_to_long_string }}</span><br />
    <span style="font-size: 1.3em">  {{ post.excerpt }}</span>
  
  {% endfor %}


---