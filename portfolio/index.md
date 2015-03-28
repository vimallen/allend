---
title: Portfolio
author: Dave Allen
layout: page
permalink: /portfolio/
---
<section class="box">
{% for job in site.data.jobs %}
<header>
<h3>{{job.name}}</h3>
</header>
<p>{{job.client}}</p>
<img src="{{job.image}}">
<a href="#">Read more...</a>
</section>
{% endfor %}


