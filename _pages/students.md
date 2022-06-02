---
layout: archive
title: "Students"
permalink: /students/
author_profile: true
---

{% include base_path %}

Students I have supervised while at BSU.   

<ul>
<li>PhD students are from our newly created interdiscplinary <a href="https://www.boisestate.edu/computing/">PhD in Computing</a> (created in Fall 2016).</li>
<li>The Department of Mathematics does not have a PhD program.</li>
<li>See my CV for list of supervisory committees I have participated in. </li>
</ul>

<h2>PhD Students</h2>
<hr style="border-width:2px; border-style:solid"/>
{% for post in site.students reversed %}
  {% include archive-single-phd-students.html %}
{% endfor %}

<h2>Master's Students</h2>
<hr style="border-width:2px; border-style:solid"/>
{% for post in site.students reversed %}
  {% include archive-single-masters-students.html %}
{% endfor %}

<h2>Undergraduate Students</h2>
<hr style="border-width:2px; border-style:solid"/>
{% for post in site.students reversed %}
  {% include archive-single-ugrad-students.html %}
{% endfor %}
