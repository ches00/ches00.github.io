---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am currently a third-year PhD student at POSTECH, advised by Prof. [Seung-Hwan Baek](https://www.shbaek.com/) in the [Computer Graphics Lab](https://cg.postech.ac.kr). My interests lie in computational imaging, computer vision, diffractive optics, and nanophotonics such as metasurfaces. My research aims to understand and utilize the wave properties of light for imaging and displays in a computational manner. I believe I can contribute to exploring next-generation cameras, lenses, displays, and sensing for smart devices, robots, autonomous vehicles, and VR/AR.

I received my Bachelor's degree in Computer Science and Engineering from POSTECH with magna cum laude honors.



News
------
{% include base_path %}
{% include news-list.html limit=5 %}
{% if site.data.news.size > 5 %}
<p><a href="{{ base_path }}/news/">More &raquo;</a></p>
{% endif %}



Publications
------
{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}
