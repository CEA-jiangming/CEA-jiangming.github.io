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
* 2014 - 2017   Ph.D in Astronomy and Astrophysics, Université Paris-Sud, France
                <br>Supervisor: <a href="http://jstarck.cosmostat.org/">Dr. Jean-Luc Starck</a>
                <br>*[Dissertation: Multichannel compressed sensing and its application in
                 radio astronomy]({% link files/thesis.pdf %})*
* 2013 - 2014   M.Res. in Image Processing, IMT Atlantique (ex-Télécom Bretagne), France
* 2010 - 2014   M.Eng. ("Diplôme d'ingénieur), IMT Atlantique (ex-Télécom Bretagne), France
* 2007 - 2010   B.S. in Electronics Engineering, Xidian University, China

Experience
======
* Since 11/2020: Tenure-Track Associate Professor, National Laboratory of Radar Signal Processing, Xidian University
* 11/2017 - 11/2020: Scientist (Post-doc)
  * LTS5, EPFL, Switzerland
  * Mentors: <a href="https://www.epfl.ch/labs/lts5/thiran-html/">Prof. Jean-Philippe Thiran</a> and <a href="https://researchportal.hw.ac.uk/en/persons/yves-wiaux">Prof. Yves Wiaux</a>

* 11/2014 - 11/2017: Doctoral Assistant
  * Cosmostat, CEA Saclay, France
  * Supervisor: <a href="http://jstarck.cosmostat.org/">Dr. Jean-Luc Starck</a>
  
* 08/2015 - 09/2015: Visitor
  * Department of Mathematics, Harbin Institute of Technology, China
  * Advisor: Prof. Jianwei Ma
   
* 04/2014 - 09/2014: Research assistant
  * Cosmostat, CEA Saclay, France
  * Supervisors: <a href="http://jstarck.cosmostat.org/">Dr. Jean-Luc Starck</a> and Prof. Erwan Deriaz
  
* 08/2013 - 09/2013: Research assistant
  * LaTIM(INSERM UMR 1101), Brest, France
  * Supervisor: Prof. Chafiaâ Hamitouche-Djabou

Research interests
======
* signal/image processing, computational imaging, machine learning, inverse problem, optimization, compressed sensing, blind source separation, radioastronomy
  
Skills
======
* Coding
  * Python (5+ years), Matlab (5+ years), C/C++ (1+ years), Java (<1 year)
  * Numpy, Scipy, Astropy, Scikit-learn, PyTorch
* Office
  * LaTeX, OpenOffice, MS Office, iWork
* Languages
  * English: professional working proficiency
  * French: professional working proficiency
  * Chinese: mother tongue

Prizes & Awards
======
* 2012, Engineering project "WelcomeSign" selected by the 2012 FIRST Program organized by Fondation Télécom
* 2009, First Prize of CUMCM (China Undergraduate Mathematical Contest in Modeling) in Shaanxi Province, China
* 2008, Second prize of 2008 Advanced Mathematics Contests in Shaanxi Province, China
* 2008, China National scholarship (awarded to top 1% undergraduate students)

Publications
======

Journal articles
------
  <ul>{% assign item_articles = site.publications | where:"type","articles" %}
  {% for post in item_articles reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Conference proceedings
------
  <ul>{% assign item_proceedings = site.publications | where:"type","proceedings" %}
    {% for post in item_proceedings reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
    
Talks and presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer of SIAM Journal on Imaging Sciences (SIIMS), IEEE Signal Processing Letters (SPL)
