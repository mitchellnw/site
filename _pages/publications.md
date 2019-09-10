---
layout: publications
permalink: /publications/
title: publications
description: publications
years: [2019]
---

## Publications

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

-----

## Preprints

{% bibliography -f preprints %}

-----


### Senior Thesis (Undergrad)


{% bibliography -f undergradthesis %}

### Awards & Honors

<ul>
    <li>AI2 Fellowship in AI (2019)</li>
    <li>Jerome L Stein Memorial Award for Undergraduate Excellence (2018)</li>
</ul>
