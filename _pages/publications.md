---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}     
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h3>Journal articles, conference proceedings, pre-prints</h3>
<hr style="border-width:2px; border-style:solid"/>
{% for post in site.publications reversed %}
  {% include archive-journal.html %}
{% endfor %}

<h3>Technical reports, posters, webpages</h3>
<hr style="border-width:2px; border-style:solid"/>
{% for post in site.publications reversed %}
  {% include archive-other.html %}
{% endfor %}
