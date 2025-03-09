---
layout: default
title: "Camera2B"
---

# 📸 Welcome to Camera2B!

Hi, I'm **Berlin**, and I love capturing moments through my camera lens. Check out my latest shots and photography adventures below!

![Sample Image](https://via.placeholder.com/800x400)

## 📷 Latest Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
