---
layout: pages
title:  "Feminist Book Club"
permalink:  "/feminist-book-club/"
category: feminist-book-club
---

# SF Feminist Book Club

<ul>
  {% for post in site.categories[page.category] %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
