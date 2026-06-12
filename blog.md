---
layout: page
title: Quant Monitor
permalink: /blog/
---

Weekly automated quantitative market monitoring logs and macro analysis reports.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      - <i>{{ post.date | date: "%B %d, %Y" }}</i>
    </li>
  {% endfor %}
</ul>
