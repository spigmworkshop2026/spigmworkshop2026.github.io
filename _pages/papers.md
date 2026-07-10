---
layout: page
permalink: /papers/
title: Accepted Papers
description: Accepted papers at SPIGM @ ICML 2026, listed by paper ID. For the poster session, please hang your poster in **Hall A**, using any available board within the following ranges: 407–416, 500–516, 600–616, or 700–708. You may use any empty space on these boards. Please note that **each board can accommodate two posters**, and do not forget to take the poster off after the poster session! Thank you!
nav: true
nav_order: 5
---

<br>

<ul>
{% for paper in site.data.papers %}
  <li><strong>{{ paper.id }}</strong>. <a href="{{ paper.forum }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></li>
{% endfor %}
</ul>
