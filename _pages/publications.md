---
layout: page
permalink: /publications/
title: Publications
description: publications by categories in reversed chronological order. generated by jekyll-scholar.
years: [2023]
nav: true
nav_order: 2
---
I don't have any publications yet but when I do they'll go here.
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
