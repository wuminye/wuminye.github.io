---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently working as a Postdoctoral Researcher in the VISICS lab, which is part of ESAT-PSI at Katholieke Universiteit Leuven, under the mentorship of [Prof. Tinne Tuytelaars](https://www.esat.kuleuven.be/psi/TT). I obtained my Ph.D. degree from the VDI Center at the School of Information Science and Technology, ShanghaiTech University, where I was supervised by [Prof. Jingyi Yu](http://www.yu-jingyi.com/cv/).

# Pubilications

{% for publication in site.publications %}
  <h2>{{ publication.title }}</h2>
  <p>{{ publication.excerpt }}</p>
{% endfor %}
