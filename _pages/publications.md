---
layout: page
title: Education
permalink: /publications/
description: Guangdong University of Foreign Studies -CHINA    2016-2020  <br>Bachelor of Economics | GAP 3.35/4
years: [1967, 1956, 1950, 1935, 1905, 2017, 2019]
nav: true
nav_order: 1
---

<b>Key courses</b>: Western economics, Accounting, Finance, International Trade, Management
<b>Mathematics course</b>: Calculus, Linear Algebra, Probability Theory, Statistics

As an Economics major student, I have taken a range of courses that have prepared me for a career in computer science. In addition to studying <b>Economics</b> and <b>Business Management</b>, I also completed several <b>Math</b> courses. These courses have provided me with a strong foundation in analytical thinking and problem-solving, which are crucial skills in the field of computer science.
After graduation, I also pursued several computer science-related courses on my own, including <b>Python</b>, <b>computer networking</b>, and <b>data structures and algorithms</b>. These gave me hands-on experience with computer technology and allowed me to get a taste of what it would be like to work in the field.

I believe my diverse educational background has thoroughly prepared me for a graduate program in CS. I am excited to continue my studies and build upon the skills and knowledge I have acquired to date.

<h3>Honors and awards</h3>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
