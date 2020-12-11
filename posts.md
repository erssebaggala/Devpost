---
layout: posts
title: Posts
sidebar_link: true
---

{% for post in site.posts %}
<a href="{{post.url}}">{{post.title}}</a>
{{post.excerpt}}
{% endfor %}
