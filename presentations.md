---
layout: default
---

# Presentations

[back](./)

{% for presentation in site.data.presentations %}
<h2> {{ presentation.venue }} <a href="{{ presentation.link }}">[url]</a> </h2>
{{ presentation.name }} <a href="{{ presentation.file }}">[pdf]</a>
{% endfor %}

[back](./)