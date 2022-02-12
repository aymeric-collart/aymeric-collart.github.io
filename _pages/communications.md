

====================================================


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
