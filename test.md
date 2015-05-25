---
layout: pagehg
title: Data Test Page
---

<ul>
{% for employer in site.data.employers %}
  <li>{{ employer.name }} {{ employer.title}}</li>
{% endfor %}
</ul>