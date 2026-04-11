---
layout: post
title: Home
---

# Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
