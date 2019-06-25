---
layout: publications
permalink: /publications/
title: publications
description: publications
years: [2019]
---

## Preprints

{% bibliography -f preprints %}


## Publications
  
{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

-----

#### Undergraduate Thesis


{% bibliography -f undergradthesis %}