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

Current Research Projects
====
</sup></sub>
<ul>{% for post in site.currentprojects reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Previous Research Projects
====
</sup></sub>
<ul>{% for post in site.previousprojects reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

Masters Research Project
====
</sup></sub>
<ul>{% for post in site.mastersproject reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>