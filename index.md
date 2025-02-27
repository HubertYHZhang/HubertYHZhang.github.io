---
layout: default
title: "Home"
---

# Welcome to My Site

## Subpages:
<ul>
  {% for page in site.pages %}
    {% if page.title and page.url != "/" %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
