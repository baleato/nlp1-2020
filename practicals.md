---
layout: photolist
title: Practicals
menu: true
---


# Practicals


{% assign practicals = (site.data.2018.assignments | where: "selected", "y") %}
{% for practical in practicals %}
{% include assignment.html lecture=practical %}
{% endfor %}

