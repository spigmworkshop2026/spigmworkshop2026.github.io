---
layout: page
permalink: /papers/
title: Accepted Papers
description: Accepted papers at SPIGM @ ICML 2026, listed by paper ID.
nav: true
nav_order: 5
---

<br>

<ul>
{% for paper in site.data.papers %}
  <li><strong>{{ paper.id }}</strong>. <a href="{{ paper.forum }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></li>
{% endfor %}
</ul>
