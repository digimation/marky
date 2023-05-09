---
layout: page
title: Blog
image: assets/img/splash/blog.jpg 
description: Beautiful Patterns is an interdisciplinary effort that seeks high-impact solutions to the complex socialtechnical challenge of women's STEM education, with and emphasis in computation, in the developing world.
---

# Welcome to the BP Blog!

01
# Recent Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.content }}</p>
    </li>
  {% endfor %}
</ul>

