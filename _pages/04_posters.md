---
layout: page
permalink: /posters/
title: Posters
description:  Here you can check all the poster contributions that I have presented. If you have any question regarding the work that I presented, please reach me through my academic socials.
years: [2022, 2020]
nav: true
heading: Poster Contributions
---


<div class="publications">



{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f events -q @*[year={{y}}]* %}
{% endfor %}

</div>