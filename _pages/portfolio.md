---
layout: archive
title: "Project Portfolio"
permalink: /portfolio/
collection: portfolio
entries_layout: grid
author_profile: true
---
{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html type=entries_layout %}
{% endfor %}
