---
layout: default
title: "Essays and Notes"
permalink: /blog/
---

### Recent Entries

<ul class="post-list">
{% for post in site.posts %}
  <li class="post-item">
    {% if post.image %}
    <a href="{{ post.url | relative_url }}" class="post-thumb">
      <img src="{{ post.image | relative_url }}" alt="{{ post.image_alt | default: post.title }}" loading="lazy">
    </a>
    {% endif %}
    <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong> — {{ post.date | date: "%B %-d, %Y" }}
  </li>
{% endfor %}
</ul>
