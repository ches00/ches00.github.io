---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am currently a Master's student at POSTECH, advised by Prof. [Seung-Hwan Baek](https://www.shbaek.com/) in the [Computer Graphics Lab](https://www.cg.postech.ac.kr). My interests lie in computer graphics, computer vision, optics, and metasurfaces. My research aims to co-design optical hardware and downstream vision software through an end-to-end optimization. I am working on computationally encoding various light properties as waves and decoding meaningful information using computer vision and graphics techniques. I believe I can contribute to exploring next-generation cameras, lenses, displays, and sensing technologies for smart devices, autonomous vehicles and VR/AR.

I received my Bachelor's degree in Computer Science and Engineering from POSTECH with magna cum laude honors. During my undergraduate studies, I acquired knowledge in system hacking and participated in the DEFCON 2019 finals as a member of the Hacking Club PLUS. I am also interested in system architectures and computer security as hobbies. Additionally, I am an avid gamer; I enjoy video games on Xbox that feature impressive graphics and storytelling, such as Hades, Baldur's Gate, The Witcher, Assassin's Creed, and the Diablo series.



News
------
- [2024.03] One paper has been accepted to <u>CVPR 2024</u> as a *highlight* paper!
- [2024.02] One paper has been accepted to <u>Nature Photonics</u> as a research article!
- [2024.02] Selected as an Outstanding Interdisciplinary Research Team at POSTECH through collabroation with [Rho's research lab](https://sites.google.com/site/junsukrho/welcome?authuser=0)!



Publications
------
{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}
