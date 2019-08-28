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


### Senior Thesis (Undergrad)


{% bibliography -f undergradthesis %}

### Awards & Honors

<ul>
    <li>AI2 Fellowship in AI (2019)</li>
    <li>Jerome L Stein Memorial Award for Undergraduate Excellence (2018)</li>
</ul>
