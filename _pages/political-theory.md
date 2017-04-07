---
layout: pages
title:  "Political Theory"
categories: tests
---

# Political Theory

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>