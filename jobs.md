---
layout: page
title: Jobs I've Held
---

<p>Here are some jobs I've held, and some information about them.</p>

<ul>
{% for employer in site.data.employers %}
  <li><b>{{ employer.name }}</b>: {{ employer.title}}<!-- Date I worked there --></li>
{% endfor %}
</ul>
