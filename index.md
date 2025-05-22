---
layout: default
title: Home
---

# Welcome to My Blog

This is where I share posts about SQL, dashboards, and machine learning.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
