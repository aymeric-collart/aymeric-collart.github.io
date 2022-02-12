---
layout: archive
title: "Publications and Presentations"
permalink: /publications-presentations/
author_profile: true

---

Page under reconstruction, please refer to my CV for my latest publications



====================================================

Test include link

[Publications](https://aymeric-collart.github.io/publications/)
 
Test include image with GitHub grammar

![Image new new description](/images/site-logo.png)

Test include image with html
 
<img src="/images/site-logo.png" alt="Image new description">


==========================

Test include image with link (github)

[![Image new new description](/images/site-logo.png)](https://aymeric-collart.github.io/publications/)

Test include image with link (html)

<a href="https://aymeric-collart.github.io/publications/">
   <img src="/images/site-logo.png" alt="Image new description">
</a>

==============================

Other tests

<h1>Select publications</h1>

{% for post in site.publications reversed %}

{% include archive-single.html %}

{% endfor %}

<hr/>
