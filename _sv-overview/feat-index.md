---
layout: base
title:  'Features'
generated: 'true'
permalink: sv/feat/index.html
---

# Features

{% include sv-feat-table.html %}

----------

Alphabetical listing

<ul>
{% for p in site.sv-feat %}
  <li><a href="{{ p.title }}.html" class="doclabel">{{ p.title }}</a>: {{ p.shortdef }}</li>
{% endfor %}
</ul>
