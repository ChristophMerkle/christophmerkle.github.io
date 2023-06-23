---
layout: archive
title: "Crowd-sourced publications"
permalink: /crowd/
author_profile: true
---

{% for post in site.crowd reversed %}
  {% include archive-single.html %}
{% endfor %}
