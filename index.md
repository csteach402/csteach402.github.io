---
title: COMP 402
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: DH Design and Programming, Spring 2016
---

Welcome to the course website for COMP 402, *DH design and programming*.

This course is offered by the [Department of Computer Science](http://www.luc.edu/cs/) and the [CTSDH](http://luc.edu/ctsdh/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}
