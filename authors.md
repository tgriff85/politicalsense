---
layout: page
title: Contributors
permalink:

---




{% for people in site.data.people %}

{{ people.name }}, {{ people.occupation }}

{% endfor %}


