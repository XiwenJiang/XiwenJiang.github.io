---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## US Accidents Analysis and Visualization Project
- **Description**: Interactive data visualization and analysis of US traffic accidents using extensive datasets
- **Technologies**: Python, Streamlit, Pandas, Plotly
- **Features**:
  - Real-time data filtering and visualization
  - Geographic accident distribution analysis
  - Weather impact analysis
  - Temporal patterns exploration

### Project Demonstrations

<div class="project-demos">
  <figure>
    <img src="/images/demo1.gif" alt="US Accidents Demo 1">
    <figcaption>Geographic Distribution Analysis</figcaption>
  </figure>

  <figure>
    <img src="/images/demo2.gif" alt="US Accidents Demo 2">
    <figcaption>Weather Impact Visualization</figcaption>
  </figure>

  <figure>
    <img src="/images/demo3.gif" alt="US Accidents Demo 3">
    <figcaption>Temporal Pattern Analysis</figcaption>
  </figure>

  <figure>
    <img src="/images/demo4.gif" alt="US Accidents Demo 4">
    <figcaption>Interactive Data Exploration</figcaption>
  </figure>
</div>

### Live Demo
<iframe src="https://xiwenjiang-us-accident-streamlit-appproject-introduction-fv70dq.streamlit.app/" 
        width="100%" 
        height="800px" 
        frameborder="0">
</iframe>

- **GitHub**: [Source Code Repository](https://github.com/XiwenJiang/US-Accident)

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

<style>
.project-demos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.project-demos figure {
  margin: 0;
  text-align: center;
}

.project-demos img {
  max-width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project-demos figcaption {
  margin-top: 10px;
  font-style: italic;
  color: #666;
}
</style>