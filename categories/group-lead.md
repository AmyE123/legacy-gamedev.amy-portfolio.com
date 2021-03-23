---
layout: page
title: Game Development
permalink: /blog/categories/group-lead/
---

<h5> Other Group Lead related work: </h5>

<div class="card">
	{% for post in site.categories.group-lead %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

