---
layout: page
title: Game Development
permalink: /blog/categories/game-jam/
---

<h5> Other Game Jam related work: </h5>

<div class="card">
	{% for post in site.categories.Game-Jam %}
		<li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</div>

