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
<p>Client: {{job.client}}</p>
<p>Description: {{job.description}}</p>
<figure><img src="{{job.image}}"></figure>
<p><a href="#">Read more &#8230;</a></p>
{% endfor %}



