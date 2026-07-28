---
layout: default
title: Honors and Awards
description: Awards and scholarships received by Minhyuk Jo.
permalink: /honors/
---

# Honors and Awards

## Awards

<ul class="timeline honors-list" role="list">
{% for item in site.data.honors.awards %}
  <li>
    <time datetime="{{ item.datetime }}">{{ item.date }}</time>
    <strong>{% if item.link %}<a href="{{ item.link | relative_url }}">{{ item.title }}</a>{% else %}{{ item.title }}{% endif %}</strong>{% if item.context %}, {{ item.context }}{% endif %}
    <span class="honor-provider">Awarded by <strong>{{ item.awarded_by }}</strong></span>
  </li>
{% endfor %}
</ul>

## Scholarships {#scholarships}

<ul class="timeline honors-list" role="list">
{% for item in site.data.honors.scholarships %}
  <li>
    <time datetime="{{ item.datetime }}">{{ item.date }}</time>
    <strong>{{ item.title }}</strong>
    <span class="honor-provider">Granted by <strong>{{ item.awarded_by }}</strong></span>
  </li>
{% endfor %}
</ul>
