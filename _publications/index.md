---
layout: default
title: Publications
---

## Peer-Reviewed Journals
{% for pub in site.publications %}
### {{ pub.title }}
**{{ pub.authors }}**  
*{{ pub.journal }}* ({{ pub.year }})  
{% if pub.doi %}[DOI](https://doi.org/{{ pub.doi }}) | {% endif %}[PDF]({{ pub.url }})
{% endfor %}

## Google Scholar (Manual Updates)
<!-- Manually add your Scholar publications here -->
- **Global stillbirths 1990–2021**  
  *GBD Collaborators (incl. Shuja KH)*  
  The Lancet (2024)  
  [DOI](https://doi.org/10.1016/S0140-6736(24)01925-1)
