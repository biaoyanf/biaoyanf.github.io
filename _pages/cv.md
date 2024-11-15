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
* Research Fellow in Bias in NLP, University of Melbourne (VIC, Australia), Jun,2022-Present 
  * Detailed achievements:
    * Created and prepared a multi-source legal dataset with a focus on the US supreme court
    * Investigated conversational behaviors in the courtroom; One related paper is under review 

* Tutor at School of Computing and Information Systems, University of Melbourne (VIC, Australia), 2020, Semester 1
  * Course: Natural Language Processing COMP90042 

* Research Assistant at InplusLab, Sun Yat-sen University (Guangzhou, China), Apr, 2017-Jun, 2018
  * Detailed Achievements: 
    * Utilized NLP methods for news detection task, predicting if it is written by machine 
    * Implemented HTCondor distributed framework to support high throughput computing
    * Jiajing Wu, Biaoyan Fang, Junyuan Fang, Xi Chen and Chi K. Tse. "Sequential topology recovery of complex power systems based on reinforcement learning", In <i>journal: Physica A: Statistical Mechanics and its Applications</i>, Vol. 535, 2019 <a href="https://www.sciencedirect.com/science/article/pii/S037843711931427X"><u>[Paper Link]</u></a>
  * Supervisor: Prof. Zibin Zheng and A/Prof. Jiajing Wu

<!-- * Tutor at School of Data and Computer Science, Sun Yat-sen University (Guangzhou, China), 2017, Semester 2
  * Course: Data structures and Algorithms -->

Awards and Additional Certificates
======
* 2022: 1st Place, <a href="https://www.alta.asn.au/events/sharedtask2022/"><u>ALTA Shared Task 2022</u></a>
* 2021: 2nd Place, <a href="https://www.alta.asn.au/events/sharedtask2021/"><u>ALTA Shared Task 2021</u></a>
* 2018-2022: Melbourne Research Scholarship
* 2017: 1st Class Scholarship (Top 5% at school)
* 2017: 1st Prize, The 26th Software Design Competition, GuangDong
* 2016: 1st Class Scholarship (Top 5% at school)
* 2016: National Scholarship (Top 1% nationwide)
* 2015: Panasonic Donation Scholarship (Top 1% at school)
  

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
        {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>


Datasets
======
  <ul>{% for post in site.publications reversed %}
    {% if post.pubtype == 'datasets' %}
        {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>


<!-- <ul>{% for post in site.publications reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul> -->


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