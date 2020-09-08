---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
======
I am a postdoc fellow in the School of Engineering and Applied Science at Harvard University. I received the B.S. and Ph.D. degrees in the School of Electrical Engineering from Korea University in Feb. 2011 and Feb. 2018, respectively. My research interests are computer vision and biomedical imaging, especially in the problems of segmentation using deep learning.

<br>

Latest News
======
{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
