---
title: Publications
permalink: /en/papers
---

# 📃 Publications

{% for paper in site.data.papers.docs %}

- [**{{ paper.title }}**]({{ paper.link }}).
{% for author in paper.authors %} {{ author }}, {% endfor %}
_{{ paper.journal }}_, {{ paper.year }}.

{% endfor %}

# 🗨️ Presentations

{% for paper in site.data.papers.presentations %}

- [**{{ paper.title }}**]({{ paper.link }}).
{% for author in paper.authors %} {{ author }}, {% endfor %}
_{{ paper.event }}_, {{ paper.place }}. {{ paper.year }}.

{% endfor %}
