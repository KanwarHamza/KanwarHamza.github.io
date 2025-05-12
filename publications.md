---
layout: default
title: Publications
permalink: /publications/
---

{% for publication in site.publications %}
  <h2>{{ publication.title }}</h2>
  <p><strong>Authors:</strong> {{ publication.authors }}</p>
  <p><strong>Year:</strong> {{ publication.year }}</p>
  <p><strong>Venue:</strong> {{ publication.venue }}</p>
  <p><a href="{{ publication.url }}">Link to Publication</a></p>
  <p><strong>DOI:</strong> <a href="https://doi.org/{{ publication.doi }}">{{ publication.doi }}</a></p>
{% endfor %}
