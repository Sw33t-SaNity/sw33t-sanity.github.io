---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
a developer and artist with a CS and Game Dev background from MSU. After working for several years, I'm now pursuing an IT Master’s in Australia. Passionate about indie games and interactive art, I love blending creativity with technology to craft unique experiences.

<div class="row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
{% include about/skills.html title="Game Engine" source=site.data.game-engine %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>


<div class="row">
{% include about/timeline.html %}
</div>