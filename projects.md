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

// Add an iframe to embed the Streamlit app
<h2>Streamlit App</h2>
<iframe src="https://xiwenjiang-us-accident-streamlit-appproject-introduction-fv70dq.streamlit.app/" width="100%" height="600px"></iframe>
