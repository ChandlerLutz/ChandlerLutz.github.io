---
permalink: /teaching-materials/
title: "Teaching Materials"
header: 
  og_image: "teaching/pdp.png"
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


