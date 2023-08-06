---
layout: page
title: Projects
---

{% for project in site.projects %}
  <h4><a href="{{ project.url }}">{{ project.title }}</a> - {{ project.date | date: "%B %Y" }}</h4>

{% endfor %}
