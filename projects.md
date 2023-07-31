---
layout: page
title: Projects
---

{% for project in site.projects %}
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  <p>{{ project.date | date_to_string }}</p>
{% endfor %}
