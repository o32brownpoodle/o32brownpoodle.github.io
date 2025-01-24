---
title: "Python Dictionary"
layout: archive
permalink: /dictionary/python/
author_profile: true
types: posts
---

{% assign posts = site.categories['d_python']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}