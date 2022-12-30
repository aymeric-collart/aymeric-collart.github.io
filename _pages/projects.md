---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}


{% assign ordered_pages = site.projects %}

{% for post in ordered_pages %} {% include archive-single.html %} {% endfor %}