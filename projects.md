---
layout: page
title: Projects
---

{% for project in site.projects %}
  <h4><a href="{{ project.url }}">{{ project.title }}</a></h4>
  <p>{{ project.date | date: "%B %Y" }}</p>

{% endfor %}
