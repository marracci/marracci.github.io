---
layout: default
title: "Writings"
permalink: /blog/
---

### Recent Entries

{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
