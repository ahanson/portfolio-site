---
layout: page
Title: Education &amp; Certifications
---

##Education:
{% for school in site.data.education %}
###{{ school.name }}, {{school.location}}

{{ school.date }}

{{ school.details }}
{% endfor %}

##Certifications:
{% for cert in site.data.certifications %}
* **{{ cert.name }}**&nbsp;{{ cert.date }}
{% endfor %}