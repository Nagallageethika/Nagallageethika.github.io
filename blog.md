---
layout: default
title: Blogs
---

# 📰 All Blog Posts (Scroll to Read)

{% for post in site.posts %}
## {{ post.title }}
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.content }}

---

{% endfor %}

