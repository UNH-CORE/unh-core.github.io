---
layout: page
title: "Publications"
description: ""
group: navigation
---
{% include JB/setup %}

Journal articles
----------------
<ul>
  {% for post in site.categories.journal-articles %}
      <li>{{ post.author }}, {{ post.year }}, <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Peer-reviewed conference papers
-------------------------------
<ul>
  {% for post in site.categories.conference-papers %}
      <li>{{ post.author }}, {{ post.year }}, <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Theses and dissertations
------------------------

Conference presentations and abstracts
--------------------------------------
