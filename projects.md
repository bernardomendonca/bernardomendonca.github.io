---
layout: page
title: Projects
---

{% for tag in site.tags %}
  <h3>{{ tag[1] }}</h3>
  <ul>
    {% for project in tag[2] %}
      <li><a href="{{ project.url }}">{{ project.date | date: "%B %Y" }} - {{ project.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
