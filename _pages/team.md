---
title: "Sai Zhang - People"
layout: gridlay
excerpt: "People"
sitemap: false
permalink: /team/
---

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4><b>{{ member.name }}</b></h4>
  {{ member.info }}
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
   <li> {{ member.education1 }}  </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  {{ member.education1 }}
  {{ member.education2 }}
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

 </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


### Former Members
<ul>
  <li> Jessica Kain (PhD student w/ Michael Snyder, Stanford Genetics, 03/2022 - 01/2023) </li>
  <li> Hantao Shu (Visiting PhD student, Tsinghua IIIS, 03/2022 - 01/2023) </li>
  <li> Han Li (Visiting PhD student, Tsinghua IIIS, 02/2022 - 09/2022) </li>
  <li> Enming Yuan (Visiting PhD student, Tsinghua IIIS, 02/2022 - 09/2022) </li>
  <li> Jia Parikh (Summer intern, Harker School, 06/2022 - 08/2022) </li>
  <li> Omar Nour Niagne (Rotation PhD student w/ Michael Snyder, Stanford Genetics, 07/2021 - 03/2022) </li>
  <li> Saahil Jain (MS student w/ Michael Snyder, Stanford CS, 09/2020 - 02/2021. Now an engineer at You.com) </li>
  <li> Xuanyi Wang (<a href="https://med.stanford.edu/genecamp.html">GRIPS</a> intern, 06/2019 - 09/2019. Now an undergraduate at UC Berkeley EECS) </li>
</ul>
