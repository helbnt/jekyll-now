---
layout: page
title: Categories
permalink: /category/
---



<ul>
{% for cat in site.categories %}
    <li>{{ cat[0] }} ({{ cat[1].size }})</li>
{% endfor %}
</ul>