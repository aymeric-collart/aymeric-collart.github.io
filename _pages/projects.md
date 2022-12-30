---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% assign ordered_pages1 = site.projects1 %}
{% for post in ordered_pages1 %} {% include archive-single.html type="grid" %} {% endfor %}

{% assign other_pages2 = site.projects2 %}
{% for post in other_pages2 %} {% include archive-single.html type="grid" %} {% endfor %}