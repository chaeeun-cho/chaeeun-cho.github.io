---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
<h3> Work in progress </h3> 

<ul>
<li>Leveraging Mutual Trade Partnerships: Examining the Role of Mutual Trade Partners on Sanction Imposition.
</ul>

<ul>
<li>Who Gets on Board? Exploring the Role of Trade Export Similarity in Determining Participation in Economic Sanctions.
</ul>

<ul>
<li>Standing Firm or Caving In? The Effect of State Control and Foreign Policy Preferences on Firms’ Exit Decisions.
</ul>

<ul>
<li>Analyzing the Impact of the U.S. Nuclear Policy on North Korea’s Nuclear Discourse during the Cold War era.
</ul>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
