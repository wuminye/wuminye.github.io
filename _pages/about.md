---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% for publication in site.publications %}
  <h2>{{ publication.title }}</h2>
  <p>{{ publication.excerpt }}</p>
{% endfor %}
