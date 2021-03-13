---
layout: page
title: Game Development
permalink: /blog/categories/3d-modelling/
---

<h5> Other 3D Modelling related work: </h5>

<div class="card">
	{% for post in site.categories.3D-Modelling %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

