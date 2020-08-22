---
layout: default
---

# Presentations

[back](./)

{% for presentation in site.data.presentations %}
  <h2 style="clear:both"> {{ presentation.venue }} <a href="{{ presentation.link }}">[link]</a> </h2>
  {% if presentation.image %}
<img src="{{ presentation.image }}" style="max-width:300px;max-height:300px">
  {% endif %}
  {{ presentation.name }} 
  <a href="{{ presentation.file }}">[pdf]</a>
{% endfor %}

<div style="clear:both"></div>
[back](./)