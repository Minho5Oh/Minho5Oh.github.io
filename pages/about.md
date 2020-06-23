---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I will add self-introduction in here

<div class="row">
{% include about/skills.html title="My Interest" source=site.data.my-interest %}
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>