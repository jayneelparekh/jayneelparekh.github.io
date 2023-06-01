---
layout: page
permalink: /publications/
title: Publications
description:  
years: [2023, 2022, 2021, 2020, 2018, 2017, 2016]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
Full list available on [Google Scholar](https://scholar.google.com/citations?user=CF7ncpUAAAAJ&hl=en)
<div class="publications" >

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]*  %}
{% endfor %} 


</div>
