---
layout: page
title: Just all pages
---

{% for p in site.pages %}
    {{ p.url  }}
{% endfor %}
