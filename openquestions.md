---
layout: page
title: Open Questions
permalink: /openquestions/
---

A list of blogs/questions I find fascinating.
I will be up for discussion about these incase anyone can contribute to my understanding of these.

{% for file in site.static_files %}
  {% if file.path contains 'questions/' %}
  <a href = "{{ site.baseurl }}{{ file.path }}">
  {{ file.basename }}
  </a>
  {% endif %}
{% endfor %}
