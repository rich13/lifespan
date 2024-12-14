---
layout: default
title: "Archive"
permalink: /archive/
---

<h1>Archive</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span> - {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>