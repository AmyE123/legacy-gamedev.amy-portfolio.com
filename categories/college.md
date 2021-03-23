---
layout: page
title: Education
permalink: /blog/categories/college/
---

<h5> Other College related work: </h5>

<div class="card">
	{% for post in site.categories.college %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

