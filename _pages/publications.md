---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024]
nav: True
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h4><strong>Authored Works</strong></h4>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}, mentioned!=true]* %}
{% endfor %}

<h4><strong>Mentioned Works</strong></h4>

{% bibliography -f {{ site.scholar.bibliography }} -q @*[mentioned=true]* %}



</div>
