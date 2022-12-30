---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign ordered_pages1 = site.projects %}
{% for post in ordered_pages1 %} {% include archive-single.html type="grid" %} {% endfor %}

{% for post in site.research %} {% include archive-second.html type="grid" %} {% endfor %}