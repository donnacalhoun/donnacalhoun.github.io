---
layout: archive
title: "Funding"
permalink: /funding/
author_profile: true
---

{% include base_path %}

List of grants awarded. 

{% for post in site.funding %}
  {% include archive-single-funding.html %}
{% endfor %}
