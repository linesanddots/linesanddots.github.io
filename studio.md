---
title: Welcome to the Studio
layout: defaultstudio
---

#Studio Events

<ul>
  {% for post in site.posts limit: 8 %}
    <li  class="conatiner" class="row-fluid">{{ post.content | truncatewords: 50}} <a href="{{ post.url }}">Read More</a></li>
  {% endfor %}
</ul>
