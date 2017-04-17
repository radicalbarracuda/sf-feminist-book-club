---
layout: index
---

# SF Feminist Book Club

[About]({{ site.baseurl }}{% link _pages/about.md %}) \| [Resources]({{ site.baseurl }}{% link _resources/index.md %})

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
