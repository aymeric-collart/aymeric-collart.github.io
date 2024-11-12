---
layout: archive
title: "Blog Posts"
permalink: /blog-posts/
author_profile: true

---

<hr />

I will share here very informal posts about anything, mostly notes and reminders for a future use.

---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}