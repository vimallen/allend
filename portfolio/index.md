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
<figure><a href=""><img src="{{job.image}}"></a></figure>
<p><a href="#">Read more &#8230;</a></p>
{% endfor %}



