---
layout: default
title: Home
---

#Conner's Homelab Blog

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    {{ post.excerpt }}
  </article>
{% endfor %}
