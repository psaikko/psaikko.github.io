---
layout: default
---

# Presentations

[back](./)

<ul>
{% for presentation in site.data.presentations %}

<li> {{ presentation.name }} <a href="{{ presentation.file }}"> [pdf] </a> </li>

{% endfor %}
</ul>

[back](./)