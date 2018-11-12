---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Resume](http://mjd3.github.io/files/Resume_21_10_2018.pdf)

Education
------
* Current EECS Ph.D student in Artificial Intelligence, UC Berkeley, 2023 (expected)
* B.S in Electrical Engineering Caltech, 2018

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Teaching
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Work Experience
------
* SpaceX (June - September 2017), _Hawthorne, CA_
  * Built high-fidelity, efficient mathematical models for Falcon 9 Rocket Power System

* Intel (June - September 2016), _Folsom, CA_
  * Power system analysis for firmware testing
