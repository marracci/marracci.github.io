---
layout: default
title: "Essays"
permalink: /blog/
---

### Recent Entries

{% for post in site.posts %}
* **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
