---
title: "Math Dictionary"
layout: archive
permalink: /dictionary/math/
author_profile: true
types: posts
---

{% assign posts = site.categories['d_math']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}