---
title: "Publications | folding space studio"
layout: textlay
excerpt: "Selected publications from the folding space studio"
sitemap: false
permalink: /publications/
---

# Publications

A selection. For a full list, see [Google Scholar](https://scholar.google.com/citations?user=srcTWI0AAAAJ&hl=en).

{% for publi in site.data.publist %}
<p>{{ publi.authors }} ({{ publi.year }}). {% if publi.url %}<a href="{{ publi.url }}">{{ publi.title }}</a>{% else %}{{ publi.title }}{% endif %}. <em>{{ publi.venue }}</em>.</p>
{% endfor %}
