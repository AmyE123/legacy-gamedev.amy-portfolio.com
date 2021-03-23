---
layout: page
title: Game Development
permalink: /blog/categories/level-design/
---

<h5> Other Level-Design related work: </h5>

<div class="card">
	{% for post in site.categories.level-design %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

