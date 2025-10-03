---
layout: default
permalink: /blogs/
title: Blogs
author_profile: false
---

<h1>Blogs</h1>

<div class="blog-list blog-post"> 
  {%- assign pages_sorted = site.pages | sort: 'date' | reverse -%}
  <ul class="blog-cards">
    {%- for p in pages_sorted -%}
      {%- if p.url contains '/blogs/' and p.url != '/blogs/' -%}
        <li class="blog-card">
          <a class="blog-card__link" href="{{ p.url }}">
            <div class="blog-card__content">       
              <!-- 日期 -->
              <div class="blog-card__date" style="font-size: 0.85rem; color: #888;">
                {{ p.date | date: "%b %-d, %Y" }}
              </div>
              <!-- 标题 -->
              <div class="blog-card__title" style="font-size: 1.2rem; font-weight: 600; color: #1a3a6d;">
                {{ p.title | default: p.url }}
              </div>
              <!-- 摘要 -->
              {%- if p.excerpt -%}
              <div class="blog-card__excerpt" style="margin-top: 0.3rem; color: #444;">
                {{ p.excerpt }}
              </div>
              {%- endif -%}
              <!-- 标签 -->
              {%- if p.tags -%}
              <div class="blog-card__meta" style="margin-top: 0.5rem;">
                {%- for t in p.tags -%}
                  <span class="tag-chip" style="display: inline-block; background: #f2f2f2; padding: 0.2rem 0.6rem; border-radius: 12px; font-size: 0.85rem; margin-right: 0.3rem; color: #333;">
                    {{ t }}
                  </span>
                {%- endfor -%}
              </div>
              {%- endif -%}
            </div>
          </a>
        </li>
      {%- endif -%}
    {%- endfor -%}
  </ul>
</div>

