---
layout: page
title: Languages
permalink: /blog/categories/blueprints/
---

<h5> Other Blueprints related work: </h5>

<div class="card">
	{% for post in site.categories.Blueprints %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

