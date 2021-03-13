---
layout: page
title: Engines
permalink: /blog/categories/console-project/
---

<h5> Other Console related work: </h5>

<div class="card">
	{% for post in site.categories.Console-Project %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

