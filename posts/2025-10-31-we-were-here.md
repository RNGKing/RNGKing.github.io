---
title: we were here
published_date: 2025-10-31 01:40:31.234331 +0000
layout: default.liquid
is_draft: false
---
## Blog!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
