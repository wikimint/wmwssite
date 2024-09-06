---
layout: default
title: "Sitemap | wmWebStack"
description: "An HTML sitemap of wmWebStack, listing all pages and their categories."
---

<h1>Sitemap</h1>

<ul>
  <li><strong>Home</strong></li>
  <ul>
    <li><a href="{{ site.url }}/">Home</a></li>
    <li><a href="{{ site.url }}/version-log">Version History & Release Notes</a></li>
    <!-- Add other specific home directory pages if necessary -->
  </ul>

  <li><strong>Documentation</strong></li>
  <ul>
    {% assign docs_pages = site.pages | where_exp: "page", "page.url contains '/docs/'" %}
    {% if docs_pages.size > 0 %}
      {% for page in docs_pages %}
        {% if page.title and page.url %}
          <li><a href="{{ site.url }}{{ page.url | remove: ".md" | remove: ".html" }}">{{ page.title | escape }}</a></li>
        {% endif %}
      {% endfor %}
    {% else %}
      <li>No documentation pages found.</li>
    {% endif %}
  </ul>

  <li><strong>Blog Posts</strong></li>
  <ul>
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.title and post.url %}
          <li><a href="{{ site.url }}{{ post.url | remove: ".html" }}">{{ post.title | escape }}</a></li>
        {% endif %}
      {% endfor %}
    {% else %}
      <li>No blog posts found.</li>
    {% endif %}
  </ul>
</ul>
