---
layout: page
permalink: /publications/
title: Publications
description: 
years: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<div class="Preprints">

  { % bibliography -- EGE_preprint %}

%{%- for y in page.years %}
 % <h2 class="year">{{y}}</h2>
  %{% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
%{% endfor %}

</div>

<div class="Publications">


</div>