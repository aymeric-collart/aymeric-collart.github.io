---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}


{% assign ordered_pages = site.projects %}

<div class="grid">
  <div id="item-1">1</div>
  <div id="item-2">2</div>
  <div id="item-3">3</div>
  <div id="item-4">4</div>
</div>

#item-1 {
    grid-column-start: 1;
    grid-column-end: 5;
}
.grid {
    display: grid;
}

{% for post in ordered_pages %} {% include archive-single.html type="grid" %} {% endfor %}