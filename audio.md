---
layout: default
title:  "Audio"
date:   2020-04-24 20:03:11
categories: [Audio]
---


<!--{% for post in site.categories.Audio %}
 <h1><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></h1>
{% endfor %}-->


<ul>
  {% for post in site.categories.Audio %}
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
    <span>{{ post.date | date_to_string }}</span>
     <span style="font-size: 1.3em"> {{ post.excerpt }}</span>
    
  {% endfor %}
</ul>

---