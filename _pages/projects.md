---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

{% for post in site.projects %} {% include archive-single-projects.html %} {% endfor %}

## Test table

<style>
.item1 { grid-area: Image; }
.item2 { grid-area: Article; }
.item3 { grid-area: Authors; }
.item4 { grid-area: Venue; }

.grid-container {
  display: grid;
  grid-template-areas:
    'Image Article'
    'Image Authors'
    'Image Venue';
  gap: 10px;
  padding: 10px;
  grid-template-columns: 35% auto;
}


</style>

<div class="grid-container">
  <div class="item1"><img align="left" width="300" height="110" src="./../images/CollartSu_Sum.png" style="padding-right:20px; padding-top:20px"/></div>
  <div class="item2">
Expressing the existence of an event with ‘you (to have) + VP’ in Taiwan Mandarin: A corpus-based investigation</div>
  <div class="item3">Collart, A.*, & Su, H.-K.</div>  
  <div class="item4">In <i>Concentric: Studies in Linguistics</i>, 2022.</div>
</div>