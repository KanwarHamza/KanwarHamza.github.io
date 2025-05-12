---
layout: default
title: Publications
---

# Publications

{% for pub in site.data.scholar.publications %}
- **{{ pub.title }}**  
  Authors: {{ pub.authors }}  
  Year: {{ pub.year }}  
  Venue: {{ pub.venue }}  
  [Link to Publication]({{ pub.url }})  
  {% if pub.doi %}DOI: [{{ pub.doi }}](https://doi.org/{{ pub.doi }}){% endif %}
{% endfor %}
