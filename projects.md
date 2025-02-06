---
layout: page
title: Projects
permalink: /projects/
---

<h1>Projects</h1>

<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url }}">{{ project.title }}</a>
      <p>{{ project.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
