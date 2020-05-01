---
layout: default
title:  "Video Archives"
date:   2020-04-24 20:03:11
categories: [Video]
---


<!--{% for post in site.categories.Video %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}-->


<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
---