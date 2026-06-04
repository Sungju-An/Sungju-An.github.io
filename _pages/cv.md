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
* M.S. in Computer Science, Gachon University, Sep. 2024 – Present
* B.S. in Future Automotive Engineering, Shinhan University, 2024

Research Interests
======
* Autonomous Driving
* Thermal Imaging
* Domain Adaptation
* Object Detection
* Edge Device

Skills
======
* Programming: Python
* Tools: Conda, Docker, CATIA

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
