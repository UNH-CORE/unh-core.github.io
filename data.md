---
layout: page
title: "Data"
description: ""
group: navigation
---
{% include JB/setup %}

Available data sets
-------------------

### 2011
<ul>
  {% for post in site.categories.datasets %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

