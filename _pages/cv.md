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
* Master's in Computer Science (Interaction, Graphics and Design), Institut Polytechnique de Paris, 2024-2026
* Bachelor's in Computer Science, Université de Bordeaux, 2021-2024
* Bachelor's in Applied Foreign Languages (English-Japanese), Université Bordeaux Montaigne, 2018-2021

Work experience
======
* Computer Science and Mathematics tutoring, Université de Bordeaux, 2023-2024
  * Teaching skills
  * In-depth knowledge of the subject taught

* Computer Science Internship, LaBRI, June 2022 - July 2022
  * Image processing and image analysis
  * Implemented algorithm for edge detection in images

* Temporary heritage assistant, CAPC, Contemporary Art Museum, October 2021 - December 2021
* Journalist assistant Internship, CINEMAXX, March 2021 - April 2021
  * Article translation
  * Video subtitling
  * Website design and management
  
Skills
======
* HTML, CSS, javascript, PSQL, D3.js
* Python, C, C++, C#, java, OCaml
* OpenGL
* Qt Creator, Android Studio
* Unity, Godot
* Cmake, make
* Git

Projects
======
<ul>{% for post in site.portfolio %}
  {% include archive-single-cv.html %}
  {% endfor %}
</ul>
