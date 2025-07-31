---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Biostatistics, University of North Carolina at Chapel Hill, 2029 (expected)
* B.S. in Applied and Computational Mathematics and Statistics, University of Notre Dame, 2024

Research Experience
======
* November 2024 - Present: Graduate Research Assistant
  * University of North Carolina at Chapel Hill, Department of Biostatistics
  * Projects: 
    * LLM embedding methods for time-varying tabular medication data in MIMIC-IV
  * Supervisor: Dr. Baiming Zou

* October 2022 - June 2024: Undergraduate Research Assistant
  * University of Notre Dame, Department of Psychology 
  * Projects: 
    * Using Learning Analytics to Support Instructors and Students in Organic Chemistry (Senior Thesis)
    * Enhancing Mastery-Based Learning: An Analytical Approach to Providing Actionable Support (Book Chapter)
  * Supervisor: Dr. Alison Cheng

* Summer 2023: Research Assistant, Summer Institute in Biostatistics
  * Boston University School of Public Health
  * Projects: 
    * Complex sample survery analysis using data from the National Health and Nutrition Examination Survey
  
Skills
======
* Programming: R, Python, Bash/Linux, Git, Docker, SQL 
* Machine Learning: PyTorch, Scikit-learn

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* UNC Biostatistics Mentorship and Advice for Prospective Students Committee 
* UNC Biostatistics Student Association Webmaster
