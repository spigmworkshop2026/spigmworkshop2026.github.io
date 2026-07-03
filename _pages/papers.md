---
layout: page
permalink: /papers/
title: Accepted Papers
description: Accepted papers at SPIGM @ ICML 2026, listed alphabetically by title.
nav: true
nav_order: 5
---

<br>

<ul>
{% assign papers = site.data.papers | sort: "title" %}
{% for paper in papers %}
  <li><strong>{{ paper.id }}</strong>. <a href="{{ paper.forum }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></li>
{% endfor %}
</ul>
