---
layout: default
---

# Projects

[back](./)

{% for category in site.data.projects.categories %}
  <h2 style="clear:both"> {{ category.name }} </h2>
  {% for project in category.projects %}
  <h3 style="clear:both"><a href="{{ project.url }}">{{ project.reponame }}</a></h3>
  {% if project.image %}
  <img src="{{ project.image }}" style="float:left;padding-right:10px;padding-bottom:10px" width="150">
  {% endif %}
  {{ project.description }}
  {% endfor %}
{% endfor %}

[back](./)