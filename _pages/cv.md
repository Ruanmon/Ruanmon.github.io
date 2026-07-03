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
* 工学硕士 Master of Engineering，电子电气专攻 Electrical and Electronic Engineering，名古屋大学 Nagoya University，2021 - 2023
* 工学学士 Bachelor of Engineering，微电子科学与工程 Microelectronics Science and Engineering，西安电子科技大学 Xidian University，2016 - 2020

Work experience
======
* 2024 - 至今 (Present): 数字IC工程师 Digital IC Engineer
  * 索尼半导体解决方案 Sony Semiconductor Solutions Corporation
  * 移动系统事业部 Mobile System Business Division

Skills
======
* 数字集成电路设计 Digital IC Design

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
