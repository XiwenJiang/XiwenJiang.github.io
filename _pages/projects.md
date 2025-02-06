---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Interactive Data Visualization Project
- **Description**: Data visualization tool built with Streamlit
- **Technologies**: Python, Streamlit, Pandas, Plotly
- **Demo**: [Watch Demo Video](your-screencast-link-here)
- **GitHub**: [Source Code](your-github-repo-link)

<video width="100%" controls>
  <source src="path-to-your-screencast.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Note: Some interactive demos may be temporarily unavailable due to technical issues. 
Please check back later or contact me for more information.

## Project Name
![Project Screenshot](/images/project-screenshot.jpg)
- **Description**: Brief description of your project
- **Technologies Used**: Python, Streamlit, etc.
- **Links**: 
  - [GitHub Repository](https://github.com/your-repo)
  - [Demo (Currently under maintenance)](https://your-streamlit-app)

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}