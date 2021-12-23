---
permalink: /teaching/
title: "Teaching"
---

Working Papers
======

{% include base_path %}

{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}


Publications
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


