---
layout: profile
title: Blog
permalink: /blog/
list_title: All Posts
---

[Home](pindra07.github.io)&nbsp;&nbsp;&nbsp;[Email](priyanshuindra3@gmail.com)

<ol class="blog-list">
  {% for post in site.posts %}
    <h1>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>&nbsp;&nbsp;&nbsp;
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </h1>
  {% endfor %}
</ol>