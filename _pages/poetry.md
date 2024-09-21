---
layout: category
title: "Poetry"
category: poetry
permalink: /daily-life/poetry/
---

This page contains all posts related to poetry. <br>
이 페이지에는 모든 시 관련 글들이 모아져 있습니다.

<ul>
  {% for post in site.categories.poetry %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
