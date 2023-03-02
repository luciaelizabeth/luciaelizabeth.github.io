---
layout: default
title: "News"
---


{% if site.show_excerpts %}
  {% include news.html %}
{% else %}
  {% include archive.html title="News" %}
{% endif %}
