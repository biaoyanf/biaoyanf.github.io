---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

CV can be downloaded <a href="https://biaoyanf.github.io/files/cv/cv.pdf"><u>here</u></a>


Education
======
* Ph.D in Computer Science (Natural Language Processing), The University of Melbourne, 2022 (expected)
* B.Eng. Information Security, Sun Yat-sen University, 2018 
  * GPA: 3.8/4.0, Ranking: 1/72 


Professional Experience
======
* Tutor at School of Computing and Information Systems, University of Melbourne (VIC, Australia), 2020, Semester 1
  * Course: Natural Language Processing COMP90042 

* Research Assistant at InplusLab, Sun Yat-sen University (Guangzhou, China), Apr, 2017-Jun, 2018
  * Detailed Achievements: 1. Implemented HTCondor distributed framework to support high throughput computing; 2. Utilized NLP methods for news detection task, predicting if it is written by machine. 3. "Sequential topology recovery of complex power systems based on reinforcement learning", paper accepted at journal: Physica A: Statistical Mechanics and its Applications  
  * Supervisor: Prof. Zibin Zheng and A/Prof. Jiajing Wu

<!-- * Tutor at School of Data and Computer Science, Sun Yat-sen University (Guangzhou, China), 2017, Semester 2
  * Course: Data structures and Algorithms -->

Awards and Additional Certificates
======
* 2018-Present Melbourne Research Scholarship
* 2017 The First Class Scholarship (Top 5% at school)
* 2017 1st Prize, The 26th Software Design Competition, GuangDong
* 2016 The First Class Scholarship (Top 5% at school)
* 2016 National Scholarship (Top 1% nationwide)
* 2015 Panasonic Donation Scholarship (Top 1% at school)
  

Skills
======
* Primary language: Python 

<!-- 
Languages
======
* English: Full Professional Proficiency
* Chinese: Native or Bilingual Proficiency -->




Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.pubtype == 'publications' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}</ul>

  <!-- <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Datasets
======
  <ul>{% for post in site.publications reversed %}
    {% if post.pubtype == 'datasets' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}</ul>
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->