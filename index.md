---
layout: default
title: Home
---
# Amber Lauer-Coles

Welcome to my website.

{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}{% endraw %}
