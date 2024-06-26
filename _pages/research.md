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
<h2>Working Papers</h2> 


<ul>
<li>Who Gets on Board? Exploring the Role of Trade Export Similarity in Determining Participation in Economic Sanctions - Job Market Paper [<a href="https://drive.google.com/file/d/1mpxQd_UWl55UzKtzsc89jLyVf1ty9EF6/preview">paper</a>, <a href="https://drive.google.com/file/d/1VQ1vC0HL5T8FK4SyAepXqi3e9e9ZyJEj/preview">slides</a>] </li>
<small> This paper explores the economic motivations driving states to join sanctions. While prior literature has largely focused on economic incentives for evading sanctions, this study highlights the potential for third-party states to engage in sanctions for economic gains. I argue that third-party states engaged in export competition with the target state may strategically join sanctioning aimed at disrupting the target's trade, thereby gaining a competitive edge in foreign markets. To test this argument, I collect an original dataset on sanctioning coalitions spanning from 1945 to 2015. I find that countries sharing similar export portfolios with the target state are more likely to join sanctioning coalitions. I also find that the target's export competitors are more likely to participate in sanctions restricting exports from the target state. This research not only offers valuable insights for policymakers tasked with designing effective sanctions regimes but also sheds new light on the substantial role of economic interests in shaping the third-party state's the decision to join sanctioning coalitions. </small>
</ul>

<ul>
<li>Influencing Beyond Your Boundaries: Shared Trade Partners and Economic Sanctions [<a href="https://drive.google.com/file/d/12-ksTmFPiWjg9MoajdUKwXARulAzlsgN/preview">paper</a>] </li>
  
<small> How the global trade network affects the initiation of sanctions threat and its success. I argue that the shared trade partner between the potential sender and the target plays an important role in shaping the sender's ability to exercise power over the target. The sender’s ability to inflict pain on the target not only comes from the sender's trade value to the target but also the sender’s economic leverage on the shared trade partners, who can influence on the outcome of sanctions by joining sanction coalitions. Employing the Threat and Imposition of Sanctions (TIES) data set, I show that states are more likely to issue sanctions threats and sanction impositions as the sender state has greater indirect leverage over the target through the shared trade partners. Furthermore, I find that while the sender's indirect leverage is positively correlated with the target's acquiescence to sanction impositions, there is no statistically significant relationship between the sender's indirect leverage and target's acquiescence to sanction threats.</small>
</ul>


<ul>
<li> Analyzing the Impact of the U.S. Nuclear Policy on North Korea’s Nuclear Discourse during the Cold War era [<a href="https://drive.google.com/file/d/18IHjOlpeKypDb8MqF2KarADwaw-UGkm5/preview">paper</a>] </li>

<small>   This paper examines how two major factors of nuclear deterrence, the U.S. nuclear weapon capability and its willingness to launch a nuclear strike have affected on changes in North Korea’s nuclear discourse in the Cold War era (1957~1986). I apply two types of automated text analysis that are useful for understanding historical changes in North Korean nuclear discourse to an original collection of 2,578 articles from Rodong Sinmun, North Korea’s official newspaper, from 1957 to 1986: macro text analysis-correlation analysis and document clustering- and micro text analysis-word frequency, network analysis and sentiment analysis-. The findings show that critical breaks of North Korea’s nuclear discourse was associated with major changes in US nuclear policies. Interestingly, the study also reveals that despite a reduction in USFK nuclear weapons capacity in the 1970s, the level of threat perception increased when the U.S. explicitly expressed its intention to launch a nuclear attack. This suggests that threat perception largely constructed by on how a country interprets the security reality surrounding its own country rather than objective assessments of material power. </small>
</ul>



<p></p>

<h2> Works In Progress </h2> 
<ul>
<li> Standing Firm or Caving In? The Effect of State Control and Foreign Policy Preferences on Firms’ Exit Decisions [<a href="https://drive.google.com/file/d/1xOYZRaVjrt_7kwlK-Z5ZLVQbAfhd_M8n/preview">slides</a>]
  
 </li>

<small> Why do some multinational corporations (MNCs) comply with economic sanctions while others continue to conduct their business with the target states? I argue that the ownership structure of firms and the foreign policy preferences of their home country are essential factors in understanding firms' decision to exit from targeted countries in response to economic sanctions. I use newly collected data on firm ownership as well as foreign policy similarity based on United Nations voting data to estimate the effect of political relations on firms’ exit decision from Russia. I find that state-owned enterprises (SOEs) are less likely to exit from the target country than private enterprises when their home country shares a close foreign policy preference with the target country. Conversely, SOEs are more likely to exit from the target country than private enterprises when their home country's foreign policy preference is distant from the target country.</small>
</ul>

<ul>
<li> Government Procurement and US Firms' Exit from the Russian Market: Evidence from the Russian invasion of Ukraine [Data Collection Stage]
 </li>

<small> In this paper, I argue that the extent to which firms rely on public procurement as a source of revenue plays a pivotal role in understanding their decisions to exit from states under economic sanctions. Using a dataset of U.S. government contracts, I estimate the effect of government contract on firms’ exit decisions from Russia.</small>

</ul>




{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
