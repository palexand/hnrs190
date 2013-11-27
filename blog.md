---
layout: frontpage
title: EECS 190 Blog
---

# EECS 190 Blog

{% for post in site.categories.blog %}
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>

{{ post.content }}

-----

{% endfor %}
