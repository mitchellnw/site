---
layout: page
title: teaching
permalink: /teaching/
description: teaching, TAing, etc. links below for more details.
---

{% for project in site.teaching reversed %}
<div>
    <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        <h3>{{ project.title }}</h3>
        <p>{{ project.description }}</p>
    </a>
</div>
{% endfor %}