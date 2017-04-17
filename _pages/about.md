---
layout: pages
title:  "About Radical Barracuda"
permalink: "/about/"
categories: about
---

# About Radical Barracuda

You have *never* met a more radical fish.

## The Feminists

{% for person in site.people %}
  {% include person.html person = person %}
{% endfor %}

