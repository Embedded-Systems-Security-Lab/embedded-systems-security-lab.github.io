---
title: Research Project Areas
nav_title: Projects
layout: default
order: 2
---

# {{ page.title }}

{% for project in site.categories.projects %}
### {{ project.title }}
{{ project.content | truncate:400 }} 
[{{ project.url }}]( ... continue reading)
{% endfor %}

