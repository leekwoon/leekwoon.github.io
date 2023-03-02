---
layout: page
title: Projects
permalink: /projects/
description: A collection of piano playing.
nav: true
---

<h3>Piano Performances</h3>
<div class="projects grid">

  {% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "piano" %}
        {% include single_project.html %}
    {% endif %}
  {% endfor %}

</div>

<h3>Research Projects</h3>

<div class="projects grid">
{% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "research" %}
        {% include single_project.html %}
    {% endif %}
  {% endfor %}

</div>