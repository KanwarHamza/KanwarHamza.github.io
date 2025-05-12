---
layout: default
title: Publications
---

Peer-Reviewed Journals

{% for pub in site.publications %}
  - {{ pub.title }}
  - Authors: {{ pub.authors }}
  - Year: {{ pub.year }}
  - Venue: {{ pub.journal }}
  - Link: [{{ pub.title }}]({{ pub.url }})
  {% if pub.doi %} DOI: [{{ pub.doi }}](https://doi.org/{{ pub.doi }}) {% endif %}
{% endfor %}
