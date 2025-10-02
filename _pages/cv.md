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
* Ph.D in Business Economics and Computer Science Engineering, Hasselt University and Ghent University, Belgium (2023)
* M.S. in Computer Science, Central University of Las Villas, Cuba (2019)  
* B.S. in Computer Science, Central University of Las Villas, Cuba (2014)  

Work experience
======
* October 2023: Postdoctoral researcher
  * Université Libre de Bruxelles

* March - September 2023: Ph.D. student
  * Faculty of Engineering and Architecture, Ghent University, Belgium

* June - September 2023: Researcher as member of Flanders Make@UHasselt
  * Hasselt University, Belgium

* December 2019 - September 2023: Ph.D. student and teaching assistant
  * Hasselt University, Belgium

* October 2017 - November 2019: Teaching assistant
  * Central University of Las Villa, Cuba

* September 2014 - September 2017: Senior Specialist in ICT
  * Company of Information Technologies for Defense, Cuba

Skills
======
* Technical skills
  * Programming Languages: Python, R, Java, Matlab
  * Libraries/frameworks: PyTorch, scikit-learn, pandas, AutomL, PyMOO, etc
  * Tools: Git, Linux, LaTeX, Microsoft Office, Arena, etc
* Analytical / Research Skills
  * Machine Learning & Deep Learning
  * Optimization techniques
  * Time series analysis
  * Data visualization & statistical analysis
  * XAI
* Professional / Transferable Skills
  * Project management
  * Scientific writing & publications
  * Collaboration in interdisciplinary teams
  * Communication & presentation
  * Problem-solving

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
