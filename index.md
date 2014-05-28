---
layout: homepage
title: Home
tagline: UNH Center for Ocean Renewable Energy
header: UNH-CORE
---
{% include JB/setup %}

Note that this is a temporary test site under construction. The official UNH-CORE site is located at
[http://unh.edu/core](http://unh.edu/core).

CORE, the UNH Center for Ocean Renewable Energy, founded in January 2008, provides multiple-scale research,
technology development and evaluation, education, and outreach for issues related to Ocean Renewable Energy 
systems.

---

<div id="home">
    {% for post in site.posts limit:4%}
      <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
      <span><i>Posted {{ post.date | date_to_string }}</i></span><br><br>
      {{ post.content | truncatewords:50 }}<br><br>
       <a href="{{ post.url }}">Read more...</a><br><br>
    {% endfor %}
</div>

<a href="posts.html"><b>Older posts &raquo;</b></a>
