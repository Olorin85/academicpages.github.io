---
title: "<h1>Past Research</h1>"
permalink: /past-research/
author_profile: true
redirect_from:
  - /past-research
---

{% include base_path %}

{% for post in site.pastresearch reversed %}
  {% include archive-single.html %}
{% endfor %}