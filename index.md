---
layout: page
title: はろーわーるど 
---
{% include JB/setup %}

## このページの説明

仕事で書いたり書かなかったりしたコードとか




##  最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
