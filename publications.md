---
layout: default
title: Publications
---

# Publications

## Impact Factor Journals

{% for publication in site.publications %}
  {% if publication.category == "impact_factor" %}
    - [{{ publication.title }}]({{ publication.url }})
      - Authors: {{ publication.authors }}
      - Journal: {{ publication.journal }}
      - Year: {{ publication.year }}
      - DOI: [{{ publication.doi }}](https://doi.org/{{ publication.doi }})
  {% endif %}
{% endfor %}

## Non-Impact Factor Journals

{% for publication in site.publications %}
  {% if publication.category == "non_impact_factor" %}
    - [{{ publication.title }}]({{ publication.url }})
      - Authors: {{ publication.authors }}
      - Journal: {{ publication.journal }}
      - Year: {{ publication.year }}
      - DOI: [{{ publication.doi }}](https://doi.org/{{ publication.doi }})
  {% endif %}
{% endfor %}

## Book Chapters

{% for publication in site.publications %}
  {% if publication.category == "book_chapter" %}
    - [{{ publication.title }}]({{ publication.url }})
      - Authors: {{ publication.authors }}
      - Journal: {{ publication.journal }}
      - Year: {{ publication.year }}
      - DOI: [{{ publication.doi }}](https://doi.org/{{ publication.doi }})
  {% endif %}
{% endfor %}
