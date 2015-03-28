---
title: Portfolio
author: Dave Allen
layout: page
permalink: /portfolio/
---

{% for job in site.data.jobs %}
<header>
<h3>{{job.name}}</h3>
</header>
<p>{{job.client}}</p>
<p>{{job.description}}</p>
<img src="{{job.image}}">
<p><a href="#">Read more...</a></p>
{% endfor %}



