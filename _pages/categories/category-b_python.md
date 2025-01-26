---
title: "Basic Python"
layout: archive
permalink: /basic/python/
author_profile: true
types: posts
---

{% assign posts = site.categories['basic_python']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}