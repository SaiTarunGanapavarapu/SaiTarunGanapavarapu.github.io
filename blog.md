---
layout: clean-page
title: Quant Monitor
permalink: /blog/
---

A weekly research memo tracking market regime, factor performance, macro signals, and notable papers from the quant finance literature.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      - <i>{{ post.date | date: "%B %d, %Y" }}</i>
    </li>
  {% endfor %}
</ul>
