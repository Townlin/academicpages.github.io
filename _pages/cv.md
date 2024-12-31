---
layout: archive
title: "个人简历 CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Physics, XX University, 20XX (expected)
* M.S. in Physics, XX University, 20XX (expected)
* B.S. in Physics, Peking University, 2027 (expected)
* 2023年毕业于安阳市第一中学
* 2020年毕业于安阳市第八中学
* 2017年毕业于安阳市三官庙小学

Work experience
======
* Winter 2024: Researcher
  * Peking University
  * Duties includes: Experiments and theory research
  * Supervisor: Xiaoji Zhou (Peking University)
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
* Currently signed in to XX different slack teams
