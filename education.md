---
layout: page
title: Education
---

##Education:
{% for school in site.data.education %}
###{{ school.name }}, <span style="font-size:large;">{{school.location}}</span>

{{ school.date }}

{{ school.details }}
{% endfor %}

##Certifications:
{% for cert in site.data.certifications %}
* **{{ cert.name }}**&nbsp;&nbsp;{{ cert.date }}
{% endfor %}