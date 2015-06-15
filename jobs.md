---
layout: standard-page
title: Work
---

Here are some jobs I've held, and some information about them.

{% for employer in site.data.employers %}
##{{ employer.name }}:
* **Title:** &ensp; {{ employer.title }} 
* **Dates Employed:** &ensp; {{ employer.dates }}

{{ employer.blurb }}
{% endfor %}

