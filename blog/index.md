---
layout: profile
title: Blog
permalink: /blog/
list_title: All Posts
---

[Home](/)&nbsp;&nbsp;&nbsp;[Email](priyanshuindra3@gmail.com)

## Blog
<ol class="blog-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>&nbsp;&nbsp;&nbsp;
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </li>
  {% endfor %}
</ol>
