---
layout: index
---

# Events

<div>
<ul>
  {% assign events = site.events | sort: 'date' %}
  {% for event in events reversed %}
  <li>
    <a href="{{ event.url | prepend: site.baseurl  }}">{{ event.title }}</a>
  </li>
  {% endfor %}
</ul>
</div>
