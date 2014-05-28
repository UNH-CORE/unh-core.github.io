---
layout: page
title: "Research"
description: ""
group: navigation
---
{% include JB/setup %}

## Hydrokinetic and wind energy

### Cross-flow turbines

#### UNH-RVAT
In the spirit of the US Department of Energy Reference Model RM2 cross-flow turbine rotor, the UNH
Reference Vertical-Axis Turbine is a simplified geometry, designed for providing high quality 
[data sets](/resources.html) for validating numerical models. 

### Turbine arrays

## Wave energy

## Senior design projects
Our TECH 797 senior design teams collaborate on ocean energy projects both in the lab and out in the field.
See the links below for more information: 

<ul>
  {% for post in site.categories.senior-design-projects %}
      <li>{{ post.date | date: "%Y" }} &ndash; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
