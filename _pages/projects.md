---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## US Accidents Analysis and Visualization Project
- **Description**: Interactive data visualization and analysis platform exploring US traffic accidents patterns and trends
- **Technologies**: 
  - Python, Streamlit, Pandas
  - Plotly, Folium for interactive visualizations
  - Data processing and statistical analysis
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
🔗 [Access the Interactive Dashboard](https://xiwenjiang-us-accident-streamlit-appproject-introduction-fv70dq.streamlit.app/)

### Project Resources
- **GitHub Repository**: [View Source Code](https://github.com/XiwenJiang/US-Accident)
- **Documentation**: [Project Details](https://github.com/XiwenJiang/US-Accident/blob/main/README.md)

---

## Other Projects

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

/* New styles for better readability */
h2 {
  color: #2c3e50;
  border-bottom: 2px solid #eee;
  padding-bottom: 10px;
  margin-top: 30px;
}

.live-demo-link {
  display: inline-block;
  margin: 20px 0;
  padding: 10px 20px;
  background-color: #3498db;
  color: white;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.live-demo-link:hover {
  background-color: #2980b9;
}
</style>