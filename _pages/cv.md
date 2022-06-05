---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[See complete CV here](https://github.com/icelu/files/bingxin_cv.pdf)

Education
======
* B.Eng. Software Engineering, East China Normal University, 2009
* M.Eng. Computer Software and Theory, East China Normal University, 2013
* Ph.D Computer Science, National University of Singapore, 2017

Work experience
======
* Postdoctoral Fellow, Genome Institute of Singapore, 2017-2018


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
