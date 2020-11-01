---
layout: page
title: Just all pages
parent: About
---

{% for p in site.pages %}
    {{ p.url  }}
{% endfor %}
