---
layout: page
title:
tagline: UNH Center for Ocean Renewable Energy
---
{% include JB/setup %}

Note that this is a temporary test site under construction. The official UNH-CORE site is located at
[http://unh.edu/core](http://unh.edu/core).

---

<div id="home">
  <h2>News</h2>
    {% for post in site.posts %}
      <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
      <span><i>Posted {{ post.date | date_to_string }}</i></span><br><br>
      {{ post.content | truncatewords:100 }}<br><br>
       <a href="{{ post.url }}">Read more...</a><br>
      <hr>
    {% endfor %}
</div>
