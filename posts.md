---
layout: default
title: "Posts"
---

{% if site.show_excerpts %}
  {% include posts.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
