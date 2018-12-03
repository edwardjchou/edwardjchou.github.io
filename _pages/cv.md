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
------
* M.S. in Computer Science, _Stanford University_, June 2019 (expected)
* B.S. in Computer Engineering, _University of Illinois at Urbana-Champaign_, May 2017

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Experience
------
* _NVIDIA Corporation_, Software Engineering Intern (May - August 2017)
  * Implemented a crypto-library testing API on Tegra chips, tested protocols including AES, DH, SHA, RSA, ECDSA, ECDH. 
  * Created an Internal Signing Utility for the HSM module, writing new utility for NVIDIA signing/encryption according to secure boot ISS 
  
* _Intel Corporation_, Software Engineering Intern (May - August 2016)
  * Worked on integrating CDMA functionality from VIA into Intel modem chips for the Apple iPhone, identifying and removing unused components and fixing build problems
  * Developed Perl scripts to replace real-time critical calculations, and other fixes like identifying unused software traces, extracting modem commands, and identifying nested semaphores.
  
* _Broadcom Corporation_, Software Engineering Intern (June - August 2015)
  * Worked with WICED Internet of Things development, primarily developed in C, used Gerrit and Git for version control
  * Developed library APIs for component and IOT protocols tests, 7 APIs deployed with Apple Homekit
