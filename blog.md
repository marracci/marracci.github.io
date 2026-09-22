---
layout: default
title: "Essays and Notes"
permalink: /blog/
---

### Recent Entries

{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
