---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Crowd-sourced Publications
======

{% include base_path %}

  <ul>{% for post in site.drafts reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>
