---
layout: page
title: Projects
---

{% for project in site.projects %}
  <h4>{{ project.date | date: "%B %Y" }} - <a href="{{ project.url }}">{{ project.title }}</a></h4>
    <p>{{ project.description }}</p>
{% endfor %}
