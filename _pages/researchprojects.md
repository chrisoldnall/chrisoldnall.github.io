---
layout: archive
title: "Research Projects"
permalink: /researchprojects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

So far, research projects I have been involved with have been wide ranging and included a vast range of stakeholders. Having started with my masters research dissertation in causal inference for epidemiology, I then worked in stochastic optimisation for CO2 removal. Following this I then worked in generalised linear modelling for public health, before now working on my full time PhD topic of causal effect estimation using Mendelian randomisation. Further details of each of these projects can be found below.

Current Research Projects
====
<ul>{% for post in site.currentprojects reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Previous Research Projects
====
<ul>{% for post in site.previousprojects reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Masters Research Project
====
As part of my MMath award, I conducted research in to causal inference in epidemiology. This thesis looks at providing the reader with some basic causal inference theory, and then follows by applying this within the epidemiological setting.

[Download dissertation here](http://chrisoldnall.github.io/files/causalinferenceepidemiology.pdf)

Recommended citation: Oldnall, Chris. (2021). "Causal Inference in Epidemiology: The Effect of Socio-economic Intervention." <i>Un-published</i>.