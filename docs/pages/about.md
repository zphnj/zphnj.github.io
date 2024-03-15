---
layout: page
title: About
description: Nanjign scenes 
keywords: Nanjing, zph
comments: true
menu: 关于
permalink: /about/
---


Welcome to "Discover Nanjing"! Delve into the city's rich history and stunning landscapes with us. From ancient dynasties to modern marvels, explore Nanjing's beauty and charm. Whether you're planning a visit or simply curious, let's uncover the secrets of this captivating city together!


## Contact

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
