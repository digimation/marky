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

02
<!-- This loops through the paginated posts -->
{% for post in paginator.posts %}
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <p class="author">
    <span class="date">{{ post.date }}</span>03
  </p>
  <div class="content">
    {{ post.content }}04
  </div>
{% endfor %}

05
<!-- Pagination links -->
<div class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}" class="previous">
      Previous 06
    </a>
  {% else %}
    <span class="previous">Previous</span> 07
  {% endif %}
  <span class="page_number ">
    Page: {{ paginator.page }} of {{ paginator.total_pages }} 08
  </span>
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}" class="next">Next</a> 09
  {% else %}
    <span class="next ">Next</span> 10
  {% endif %}
</div>

# new block
    {% if site.paginate %}
      <div class="pager">
        <ul class="pagination">
        {%- if paginator.previous_page %}
          <li><a href="{{ paginator.previous_page_path | relative_url }}" class="previous-page">{{ paginator.previous_page }}</a></li>
        {%- else %}
          <li><div class="pager-edge">•</div></li>
        {%- endif %}
          <li><div class="current-page">{{ paginator.page }}</div></li>
        {%- if paginator.next_page %}
          <li><a href="{{ paginator.next_page_path | relative_url }}" class="next-page">{{ paginator.next_page }}</a></li>
        {%- else %}
          <li><div class="pager-edge">•</div></li>
        {%- endif %}
        </ul>
      </div>
    {%- endif %}