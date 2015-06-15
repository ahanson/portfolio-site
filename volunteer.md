---
layout: standard-page
title: Volunteering
---

I've been volunteering regularly since I was in high school.

{% for organization in site.data.organizations %}
##{{ organization.name }}:
* **Title:** &ensp; {{ organization.title }} 
* **Dates Employed:** &ensp; {{ organization.dates }}

{{ organization.blurb }}
{% endfor %}

