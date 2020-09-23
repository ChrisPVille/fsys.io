---
layout: default
title: Blog
nav_order: 2
description: ""
permalink: /blog
---

## Development Blog

I'll generally try to keep things organized on project pages, but sometimes information doesn't fit neatly into those buckets and will appear here.

<ul class="posts">
   {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>
