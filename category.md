---
layout: page
title: Categories
permalink: /category/
---

{% capture cats %}
{% for cat in site.categories %}
  {{ cat[0] }} ({{ cat[1].size }})
{% endfor %}
{% endcaptire%} 

{% assign sortedcats = cats | split:' ' | sort %}
{% for cat in sortedcats reversed %}
    {% assign catitems = cat | split: '#' %}
    <ul>
    <li><a href="/category/{{ catitems[0] }}">{{ catitems[0] }} ({{ catitems[1] }})</a></li>
    </ul>
{% endfor %}

<h3>twat</h3>