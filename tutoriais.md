---
layout: page
title: Tutoriais
permalink: /tutoriais/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h3>{{ post.title }}</h3>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>