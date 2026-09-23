---
title: "In the conversation | folding space studio"
layout: textlay
excerpt: "People in the conversation at the folding space studio"
sitemap: false
permalink: /conversation/
---

# In the conversation

The studio is a larger collaboration of likeminded people, at UBC and well beyond it. Students and collaborators often work on topics not directly related to one another's, but remain in vigorous intellectual conversation. Their work spans cultural critique and technically creative, generative work, theoretical and empirical, qualitative and ethnographic as well as computational.

{% for person in site.data.conversation %}
<p><strong>{% if person.url %}<a href="{{ person.url }}">{{ person.name }}</a>{% else %}{{ person.name }}{% endif %}</strong><br />
{{ person.info }}</p>
{% endfor %}

Anyone interested in speaking, studying, and/or collaborating with us, please [reach out](mailto:luke.bergmann@ubc.ca).
