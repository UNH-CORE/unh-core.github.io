---
layout: page
title: "Facilities"
description: "A page for listing facilities descriptions."
group: navigation
---
{% include JB/setup %}

<ul class="nav">
  {% assign pages_list = site.pages %}
  {% assign group = 'facilities' %}
  {% include JB/pages_list %}
</ul>
