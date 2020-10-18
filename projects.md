---
title: Our Work
layout: default
permalink: /projects/
---

## Current Projects
The following initiatives are currently underway and accepting contributors. Projects are open to volunteers of all skillsets.

{% for project in site.data.projects.active %}
{% include projects/project-card.html %}
{% endfor %}

---
## Former Projects

{% for project in site.data.projects.former %}
{% include projects/project-card.html %}
{% endfor %}