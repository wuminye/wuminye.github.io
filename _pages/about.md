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



<div class="row">
  <div class="column" style="float: left; width: 50%;">
    <!-- 第一列内容 -->
    <h3>Research Interests</h3>
    <ul>
      <li>computational photography</li>
      <li>computer vision</li>
    </ul>
  </div>
  <div class="column" style="float: right; width: 50%;">
    <!-- 第二列内容 -->
    <h3>Education</h3>
    <ul>
      <li>Ph.D.: University of Chinese Academy of Sciences, 2021</li>
      <li>Bachelor: Shanghai University, 2015</li>
    </ul>
  </div>
</div>
<div style="clear: both;"></div>


# Pubilications

{% for publication in site.publications %}
  <h2>{{ publication.title }}</h2>
  <p>{{ publication.excerpt }}</p>
{% endfor %}
