---
layout: page
title: Languages
permalink: /blog/categories/cplusplus/
---

<h5> Other C++ related work: </h5>

<div class="card">
	{% for post in site.categories.CPlusPlus %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

