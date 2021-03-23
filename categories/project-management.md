---
layout: page
title: Game Development
permalink: /blog/categories/project-management/
---

<h5> Other Project Management related work: </h5>

<div class="card">
	{% for post in site.categories.project-management %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

