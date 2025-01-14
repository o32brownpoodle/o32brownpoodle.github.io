---
title: "Statistics"
layout: archive
permalink: /math/statistics/
author_profile: true
types: posts
---

{% assign posts = site.categories['statistics']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}