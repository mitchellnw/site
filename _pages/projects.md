---
layout: page
title: misc
permalink: /misc/
description: in progress.
---

{% for project in site.projects reversed %}
<div>
    <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        <h4>{{ project.title }}</h4>
        <p>{{ project.description }}</p>
    </a>
</div>
{% endfor %}
