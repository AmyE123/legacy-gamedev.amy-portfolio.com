---
layout: page
title: Study
permalink: /blog/categories/self-directed-study/
---

<h5> Other Self Directed Study blogs: </h5>

<div class="card">
	{% for post in site.categories.self-directed-study %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

