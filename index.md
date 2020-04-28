---
title: Welcome
---

# Preferences for Image-Guidance Survey

We are currently updating the survey, and anticipate it being available again on Wednesday the 6th of May. Please check back then.

<!--
If you are seeking to participate in the Preferences for Image-Guidance survey please click here:

<a href="#" class="survey-link">ENTER SURVEY</a>
-->

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
