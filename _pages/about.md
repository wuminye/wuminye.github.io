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
  <div class="column" style="float: left; width: 40%;">
    <!-- 第一列内容 -->
    <h3>Research Interests</h3>
    <ul>
      <li>Neural Rendering</li>
      <li>computer vision</li>
      <li>computational photography</li>
    </ul>
  </div>
  <div class="column" style="float: right; width: 60%;">
    <!-- 第二列内容 -->
    <h3>Education</h3>
    <ul>
      <li>[Ph.D.] University of Chinese Academy of Sciences, 2021</li>
      <li>[Bachelor] Shanghai University, 2015</li>
    </ul>
  </div>
</div>
<div style="clear: both;"></div>


# Pubilications

{% for publication in site.publications %}
  <h2>{{ publication.title }}</h2>
  <p>{{ publication.excerpt }}</p>
{% endfor %}



<!-- Default Statcounter code for homepage https://wuminye.github.io/ -->
<script type="text/javascript">
var sc_project=12948099; 
var sc_invisible=1; 
var sc_security="0b88a620"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js" async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img class="statcounter"
src="https://c.statcounter.com/12948099/0/0b88a620/1/" alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->