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
<h3> Works In Progress </h3> 

<ul>
<li>Leveraging Mutual Trade Partnerships: Examining the Role of Mutual Trade Partners on Sanction Imposition
  </li>
</ul>

<ul>
<li>Who Gets on Board? Exploring the Role of Trade Export Similarity in Determining Participation in Economic Sanctions
 </li>
  This paper explores the motivations behind states joining economic sanctions. While prior literature has largely focused on economic incentives for breaking sanctions, this study highlights the potential for third-party states to join sanctions for economic reasons. Specifically, third-party states that compete with the target state for similar exports may disrupt trade to gain a competitive edge in foreign markets. By analyzing commodity-level trade data from 1962 to 2015, this study finds that countries that share similar export portfolios with the target are more likely to join sanctioning coalitions.
</ul>

<ul>
<li>Standing Firm or Caving In? The Effect of State Control and Foreign Policy Preferences on Firms’ Exit Decisions [Research Design Stage]
 </li>
</ul>

<ul>
<li>Analyzing the Impact of the U.S. Nuclear Policy on North Korea’s Nuclear Discourse during the Cold War era
 </li>
</ul>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
