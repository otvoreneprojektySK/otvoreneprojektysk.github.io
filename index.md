---
layout: page
title: Otvorené Projekty (.sk)
tagline: Vitajte na "centrálnom rozcestníku".
---

Ešte sa sem nepozerajte, nič tu nie je ;)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

[//]: # (komentar)
