---
layout: post
title:  "The Important People"
date:   2018-03-06 20:54:00 -0500
categories: something
---

Here are the most important people in the world:

<ul class="list-group">
  {% for person in site.data.people %}
  <li class="list-group-item">
    {{ person.name }} -- {{ person.position }}
  </li>
  {% endfor %}
</ul>