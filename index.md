---
title: Welcome
---




# Latest

<!-- list of blog posts with excerpts -->
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}" class="post-list-title">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
