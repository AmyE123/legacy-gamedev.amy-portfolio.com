---
layout: page
title: Game Development
permalink: /blog/categories/design/
---

<h5> Other Design related work: </h5>

<div class="card">
	{% for post in site.categories.Design %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

