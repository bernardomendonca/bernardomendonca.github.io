---
layout: page
title: Projects
---

{% for project in site.projects %}
  <h4>{{ project.date | date: "%Y" }} - <a href="{{ project.url }}">{{ project.title }}</a></h4>
{% endfor %}
