---
layout: page
title: Work
---

<p>Here are some jobs I've held, and some information about them.</p>

{% for employer in site.data.employers %}
##{{ employer.name }}:
* **Title:** &ensp; {{ employer.title}} 
* **Dates Employed:** &ensp; {{employer.dates}}
{% endfor %}

