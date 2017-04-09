---
layout: pages
title:  "Political Theory"
permalink:  "/political-theory/"
categories: tests
---

# Political Theory

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
