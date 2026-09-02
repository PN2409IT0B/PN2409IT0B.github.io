---
layout: default
title: Posts
permalink: /posts.html
---

<ul class="post-list">
{% for post in site.posts %}
  <li class="post-item">
    <a href="{{ post.url | relative_url }}" class="post-title">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
  </li>
{% else %}
  <p>No posts published yet!</p>
{% endfor %}
</ul>