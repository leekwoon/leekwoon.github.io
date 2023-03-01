---
layout: page
title: Piano
permalink: /projects/
description: A collection of piano playing.
nav: true
---

<h3>Concert</h3>
<div class="projects grid">

  {% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "concert" %}
        {% include single_project.html %}
    {% endif %}
  {% endfor %}

</div>

<h3>Practice</h3>

<div class="projects grid">
{% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "practice" %}
        {% include single_project.html %}
    {% endif %}
  {% endfor %}

</div>