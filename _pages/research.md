---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

Chandler's research employs econometric, statistical, and machine learning methods in the study of housing economics and housing policy, labor markets, and monetary policy. His research has been published in the [*Review of Financial Studies*](https://academic.oup.com/rfs/article-abstract/34/2/864/5842150), the [*Journal of Labor Economics*](https://www.journals.uchicago.edu/doi/abs/10.1086/703579), and the [*Journal of Urban Economics*](https://www.sciencedirect.com/science/article/abs/pii/S0094119016300419), among other outlooks. In recent work, he has developed [new datasets](https://github.com/ChandlerLutz/LandUnavailabilityData) that measure the amount of [land unavailable for housing construction](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3478900) across the United States and causally assessed the impact of [interest rate declines on distressed borrowers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3869199).

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


