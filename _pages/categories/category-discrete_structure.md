---
title: "Discrete Structure"
layout: archive
permalink: /ai/discrete_structure/
author_profile: true
types: posts
---

{% assign posts = site.categories['discrete_structure']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}