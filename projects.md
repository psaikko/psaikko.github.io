---
layout: default
---

# Projects

[back](./)

{% for category in site.data.projects.categories %}
  <h2> {{ category.name }} </h2>
  <ul>
  {% for project in category.projects %}
    <li> <a href="{{ project.url }}">{{ project.reponame }}</a> </li>
  {% endfor %}
  </ul>
{% endfor %}

[back](./)