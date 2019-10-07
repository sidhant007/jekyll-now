---
layout: page
title: Open Questions
permalink: /openquestions/
---

{% for file in site.static_files %}
  {% if file.path contains 'questions/' %}
  <a href = "{{ site.baseurl }}{{ file.path }}">
  {{ file.basename }}
  </a>
  {% endif %}
{% endfor %}
