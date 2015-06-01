---
layout: page
title: Jobs
---

<p>Here are some jobs I've held, and some information about them.</p>

<ul>
{% for employer in site.data.employers %}
  <li><b>{{ employer.name }}</b>: {{ employer.title}} {{employer.dates}}</li>
{% endfor %}
</ul>
