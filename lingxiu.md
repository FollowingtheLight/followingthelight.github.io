---
layout: page
title: "灵修分类"
permalink: /categories/devotion/
---

{% for post in site.categories.devotion %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
