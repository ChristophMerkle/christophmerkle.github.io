---
layout: archive
title: "Crowd-sourced publications"
permalink: /crowd/
author_profile: true
---

{% include base_path %}

{% for post in site.crowd reversed %}
  {% include archive-single.html %}
{% endfor %}
