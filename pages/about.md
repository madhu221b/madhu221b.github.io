---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
<p> I currently work as a full stack developer at Credit Suisse. I  received my degree of Bachelor's in Computer Engineering in 2019.</p>
<p>I hail from a small town - Nashik, India. I love reading books, gardening, trying my hand at cooking and sometimes painting. I sometimes write stories, poems and draw comics. I am currently learning Spanish language. I believe in giving back to society and as someone with technology background, I am passionate about solving real-time problems which have a social impact. I am looking for opportunities to do interesting development or AI/ML projects which would help me grow as well as prove to be valuable to the organization.</p>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Database Skills" source=site.data.database-skills %}
<!-- {% include about/skills.html title="Other Skills" source=site.data.other-skills %} -->
</div>

<div class="row">
{% include about/timeline.html %}
</div>