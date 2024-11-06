---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

paraprapapapap

<nbsp>

<div style="text-align: justify; text-justify: inter-word;">

My academic research falls into three main areas: (1) Physics-informed model-order reduction, (2) Turbulence dynamics, and (3) Laminar-turbulent transition
in high-speed flows. Feel free to check out!

</div>

<br/><br/>
<br/><br/>
<br/><br/>
<br/><br/>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

<nbsp>






