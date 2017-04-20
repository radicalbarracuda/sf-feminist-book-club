---
layout: default
---

# Events

<div>
  <ul>
    {% assign events = site.events | sort: 'datetime' %}
    {% for event in events reversed %}
    <li>
      <a href="{{ event.url | prepend: site.baseurl  }}">{{ event.title }}</a>
    </li>
    {% endfor %}
  </ul>
</div>
