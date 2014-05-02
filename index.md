---
layout: page
title: 
tagline: UNH Center for Ocean Renewable Energy
---
{% include JB/setup %}

Note that this is a temporary test site under construction. The official UNH-CORE site is located at
[http://unh.edu/core](http://unh.edu/core).

<div id="home">
  <h2>News</h2>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
