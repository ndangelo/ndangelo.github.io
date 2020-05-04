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
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

---