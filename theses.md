---
layout: default
---

# Theses

[back](./)

{% for thesis in site.data.theses %}
<h3> {{ thesis.type }} </h3> 
{{ thesis.title }} <a href="{{ thesis.file }}"> [pdf] </a>

{{ thesis.description }}
{% endfor %}

[back](./)