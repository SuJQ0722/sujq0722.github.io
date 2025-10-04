---
layout: default
permalink: /blogs/
title: Blogs
author_profile: true
---

<h1>Blogs</h1>

<div class="blog-list blog-post"> 
  {%- assign blog_pages = site.pages | where_exp: 'p', "p.url contains '/blogs/'" | reject: 'url', '/blogs/' | where_exp: 'p', 'p.title' | sort: 'date' | reverse -%}
  <ul class="blog-cards">
    {%- for p in blog_pages -%}
      {% include blog_card.html p=p %}
    {%- endfor -%}
  </ul>
</div>

