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
<div class="Publications">

%{%- for y in page.years %}
% 	<h2 class="year">{{y}}</h2>
  %{% bibliography -f papers -q @*[year={{y}}]* %}
%{% endfor %}

%{% bibliography %}


</div>