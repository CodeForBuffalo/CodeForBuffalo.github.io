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

---
## Identified a problem in your community?
Maybe Code for Buffalo can help and we can address that problem together. You can submit a problem statement to our core team using the button at the bottom of this page. Before you submit, please make sure your submission is in line with our few ground-rules below.

### How we take on new projects
{% include projects/project-rules.html %}

