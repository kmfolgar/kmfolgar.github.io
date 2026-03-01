---
layout: default
title: "Blog"
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <p><em>{{ post.date | date: "%B %e, %Y" }}</em></p>
      {{ post.excerpt }}
      <p><a href="{{ site.baseurl }}{{ post.url }}">Read more</a></p>
    </article>
  {% endfor %}
</div>
