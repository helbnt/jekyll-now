---
layout: page
title: Categories
permalink: /category/
---

<!--

<ul>
{% for cat in site.categories %}
    <li>{{ cat[0] }} ({{ cat[1].size }})</li>
{% endfor %}
</ul>
-->
{% capture cats %}
  {% for cat in site.categories %}
    {{ cat[1].size | plus: 1000 }}#{{ cat[0] }}#{{ cat[1].size }}
  {% endfor %}
{% endcapture %}
{% assign sortedcats = cats | split:' ' | sort %}
{% for cat in sortedcats reversed %}
    {% assign catitems = cat | split: '#' %}
    <li><a href="/cats/#{{ catitems[1] }}">{{ catitems[1] }} ({{ catitems[2] }})</a></li>
{% endfor %}

<h3>twat</h3>