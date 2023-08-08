---
layout: page
title: Blog Archive
---

{% for post in site.posts %}
    <li>{{ post.date | date: "%B %Y" }} <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
