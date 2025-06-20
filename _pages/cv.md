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
=======
* Ph.D. Candidate in Bioinformatics, University of British Columbia
* B.Sc. in Electrical Engineering (first major), Isfahan University of Technology
* B.Sc. in Applied Mathematics (second major), Isfahan University of Technology


Experience
======
* Graduate Research Assistant, University of British Columbia

Research Interests
======
* Machine Learning: Multi-Modal Representation and Semantic Representation
* Large Vision and Language Foundation Models 
* Mathematical Modeling and Computational Pathology 

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
* Engaged member of the UBC research community
