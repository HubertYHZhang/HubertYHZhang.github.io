---
layout: default
title: "Home"
---

# Welcome to My Site

<!-- <link rel="icon" type="image/x-icon" href="images/my-notion-face-customized.png"> -->

## Subpages:
<ul>
  {% for page in site.pages %}
    {% if page.title and page.url != "/" %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
