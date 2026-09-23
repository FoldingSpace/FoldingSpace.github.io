---
title: "In the conversation | folding space studio"
layout: textlay
excerpt: "People in the conversation at the folding space studio"
sitemap: false
permalink: /conversation/
---

# In the conversation

The Folding Space Studio is convened by Luke Bergmann yet brings into a larger collaboration of likeminded people, at UBC and well beyond it. Students and collaborators often work on topics not directly related to one another's, but remain in vigorous intellectual conversation. Their work spans cultural critique and technically creative, generative work, theoretical and empirical, qualitative and ethnographic as well as computational. Anyone interested in speaking, studying, and/or collaborating with us, please [reach out](mailto:luke.bergmann@ubc.ca).

{% for person in site.data.conversation %}{% unless person.outside %}
<p><strong>{% if person.url %}<a href="{{ person.url }}">{{ person.name }}</a>{% else %}{{ person.name }}{% endif %}</strong><br />
{{ person.info }}</p>
{% endunless %}{% endfor %}

<p>...and a number of current students.</p>

#### Outside of UBC, including...

{% for person in site.data.conversation %}{% if person.outside %}
<p><strong>{% if person.url %}<a href="{{ person.url }}">{{ person.name }}</a>{% else %}{{ person.name }}{% endif %}</strong><br />
{{ person.info }}</p>
{% endif %}{% endfor %}
