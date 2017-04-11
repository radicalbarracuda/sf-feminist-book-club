---
layout: pages
title:  "Anarchism in Theory & Practice"
permalink:  "/anarchist-book-club/"
category: anarchist-book-club
---

# Anarchism in Theory & Practice

<ul>
  {% for post in site.categories[page.category] %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
