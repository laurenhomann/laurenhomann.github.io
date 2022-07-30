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
* **Ph.D in Psychology,** University of Toronto, 2027 (expected)
* **Honours B.Sc in Psychology,** Minor in Biology, University of Waterloo, 2022
  * *Honours Thesis:* The effects of self-selected background music and task difficulty on task engagement and performance in a visual vigilance task

Publications
======
  <ol>
    {% assign sorted = site.publications | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% include archive-single-cv.html %}
    {% endfor %}
  </ol>
<hr>

Conference Presentations
======
  <ol>
    <li>Homann, L. A., Roberts, B. R. T., Ahmed, S., Fernandes, M. A. (2021, November 4-7). Are emojis processed visuo-spatially or verbally? Evidence for dual codes [Poster presentation]. Psychonomic Society 62nd Annual Meeting, Online. </li>
  </ol>
<hr>

Honours and Awards
======
* **Canada Graduate Scholarship–Masters**, 2022
  * Awarded by: Natural Sciences and Engineering Research Council of Canada (NSERC)
  * Purpose: The CGS M program provides financial support to high-calibre scholars engaged in eligible masters, or in some cases, doctoral programs in Canada.  Value: $17,500.
* **Recruitment Award**, 2022
  * Awarded by: University of Toronto, Department of Psychology
  * Value: $5,000
* **Honours Thesis Award**, 2022
  * Awarded by: University of Waterloo, Department of Psychology
  * Purpose: The Department of Psychology recognizes the achievements of a small number of students who produced the most outstanding honours theses.
* **Undergraduate Student Research Award**, 2020
  * Awarded by: Natural Sciences and Engineering Research Council of Canada (NSERC)
  * Purpose: Purpose: To provide full-time research experience which will encourage students to consider graduate studies and pursue careers in the natural sciences and engineering. Value: $4,500.
* **University of Toronto Scholars Award**, 2016
  * Awarded by: University of Toronto
  * Purpose: A scholarship issued to high achieving students upon entry to the University of Toronto. By selection. Value: $6,000.
<hr>

Work experience
======
* **Honours Thesis Student and Research Assistant**, Jan. 2021-present
  * Vision and Attention Lab, Department of Psychology, University of Waterloo
  * Supervisor: Dr. Daniel Smilek


* **Research Assistant**, Jan. 2020-May 2022
  * Cognitive Neuroscience Lab, Department of Psychology, University of Waterloo
  * Supervisor: Dr. Myra Fernandes

* **Research Assistant**, May 2019-Aug. 2020
  * Psychological Interventions Research Team, Department of Psychology, University of Waterloo
  * Supervisor: Dr. Jonathan Oakman
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
