---
layout: archive
title: "Publications and Presentations"
permalink: /publications-presentations/
author_profile: true

---

Test with new text

{% include base_path %}

{% assign ordered_pages = site.PublicationsPresentations | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
