---
layout: page
title: Game Development
permalink: /blog/categories/personal-project/
---

<h5> Other Personal Project work: </h5>

<div class="card">
	{% for post in site.categories.Personal-Project %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

