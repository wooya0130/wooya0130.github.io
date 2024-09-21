---
layout: post
title: "Poetry"
category: poetry
permalink: /daily-life/poetry/
---

This page contains all posts related to poetry. <br>
이 페이지에는 모든 시 관련 글들이 모아져 있습니다.

<ul>
  {% assign poetry_posts = site.categories.poetry | uniq %}
  {% for post in poetry_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
