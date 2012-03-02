---
layout: page
title: Yay!
---
{% include JB/setup %}

Hello. This website is mostly for testing. These are my current blog posts. Thanks.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>