---
layout: page
title: Category
permalink: /category/
---

<h2>Essay</h2>

<ul>
{% for cat in site.categories %}
    <li>{{ cat[0] }} ({{ cat[1].size }})</li>
{% endfor %}
</ul>