---
layout: index
---

# SF Feminist Book Club

Is awesome!

[About]({{ site.baseurl }}{% link _pages/about.md %})
[Resources]({{ site.baseurl }}{% link _resources/index.md %})

## Study Guides
<ul>
  {% for post in site.posts %}
    {% if post.categories contains 'study-guides' %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
    {%endif %}
  {% endfor %}
</ul>

