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
* M.S. in Computer Science, East China University of Science and Technology, 2021-2024
* B.S. in Food Quality and Safety, East China University of Science and Technology, 2013-2017

Work experience
======
* Summer 2023: Deep Learn Algorithm Intern
  * Company: *Attrsense*
  * Duties included: In our research on car plate detection and recognition, we use YOLOv7 to detect the plate and the CRNN model to recognize the plate numbers. We need to apply the system to edge devices for real-time and achieve over 90% accuracy on real crossroads.

* Summer 2022: Computer Vision Algorithm Intern
  * company: *FOSUN Aitrox*
  * Duties included: We try to deal with the unbalanced labels in medical image classification. In the intern days, we used dataset balance, data augmentation, and metric learning to solve some issues.
  
Skills
======
* Python, Pytorch, Jittor etc.
* Linux, C/C++
* Computer Vision

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Activities
======
  <ul>{% for post in site.activities %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!--Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
