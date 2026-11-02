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
* Ph.D in Engineering Physics, McMaster University, Hamilton, Ontario, Canada (2022)
* B.S. in Materials Science and Nanoengineering, Sabanci University, Istanbul, Turkiye (2018)

Work experience
======
* July 2024: Postdoctoral Researcher
  * Engineering Physics, McMaster University
  * Supervisor: Prof. Niko Hildebrandt

* August 2023 - July 2024: Instructional Assistant 
  * Engineering Physics, McMaster University

* January - August 2023: Postdoctoral Researcher, 
  * Department of Physics, Concordia University
  * Supervisor: Prof. Ayse Turak
  
Research Interests
======

- Optical ion sensing
- Thin-film optodes
- Colloidal quantum dots
- Nanoparticle self-assembly
- Fluorescence spectroscopy
- Water-quality monitoring
- Semiconductor devices
- Renewable energy materials
- Computational materials science
- Photoelectrochemical systems

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Guest Lectures
======
<ul>
{% for post in site.guest_lectures reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>
 
Thesis
======
 <ul>{% for post in site.publications reversed %}
  {% if post.category == "theses" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

Publications
======
 <ul>{% for post in site.publications reversed %}
  {% if post.category == "manuscripts" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>
  
Conference Proceedings
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Skills
======
### Materials Synthesis

- Colloidal nanoparticle synthesis
- Surface functionalization
- Thin-film fabrication
- Ceramic processing

### Characterization

- UV-Vis spectroscopy
- Fluorescence spectroscopy
- Raman spectroscopy
- FTIR spectroscopy
- Atomic force microscopy (AFM)
- Electron microscopy
- Voltammetry
- Interferometry

### Computation

- Python
- MATLAB
- Image analysis
- Computer vision
- Data analysis
- Scientific visualization

### Design & Fabrication

- CAD
- 3D printing
- Semiconductor processing
- Cleanroom techniques
  
Service and leadership
======
* 
