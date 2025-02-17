---
layout: default
title: "Blog Posts"
permalink: /blog/
---

# Blog Posts

Here are my latest blog posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small> - {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
