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

{% capture tags %}
  {% for tag in site.tags %}
    {{ tag[1].size | plus: 1000 }}#{{ tag[0] }}#{{ tag[1].size }}
  {% endfor %}
{% endcapture %}
{% assign sortedtags = tags | split:' ' | sort %}
{% for tag in sortedtags reversed %}
    {% assign tagitems = tag | split: '#' %}
    <li><a href="/tags/#{{ tagitems[1] }}">{{ tagitems[1] }} ({{ tagitems[2] }})</a></li>
{% endfor %}

<h3>twat</h3>