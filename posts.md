---
layout: posts
title: Posts
sidebar_link: true
---

{% for post in site.posts %}
<a href="{{ post.url | relative_url }}">{{post.title}}</a>
{{post.excerpt}}
{% endfor %}
