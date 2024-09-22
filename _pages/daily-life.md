---
layout: default
title: "Daily Life"
permalink: /daily-life/
---

<div id="main" role="main">
  {% include sidebar.html %}

   <!-- 본문 상단에 추가할 글 -->
  <p>I’ll be showing you all aspects of my daily life, hobbies, and fascinating experiences.</p>
  <p>나의 일상, 취미, 흥미로운 일들을 모두 보여줄께.</p>

  <article class="page h-entry" itemscope itemtype="https://schema.org/CreativeWork">
    <div class="page__inner-wrap">
      <header>
        <h1 class="page__title">{{ page.title }}</h1>
      </header>

      <section class="page__content">
        <h2>Category</h2>
        <ul>
          <li><a href="/categories/poetry/">Poetry</a></li>
          <li><a href="/categories/travel/">Travel</a></li>
        </ul>
      </section>
      
    </div>
  </article>
</div>
