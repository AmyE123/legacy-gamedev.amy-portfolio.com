---
layout: page
title: Engines
permalink: /blog/categories/unity/
---

<h5> Other Unity related work: </h5>

<div class="row">
	{% for post in site.categories.unity %}
        <div class="card blog-post" style="border-radius: 50px">
            <img class="card-img-top" src="{{site.url}}{{site.baseurl}}{{ post.thumbnail }}" alt="{{ post.title }}" style="border-radius: 30px">
            <div class="card-body center">
                <!-- <img src="{{site.url}}{{site.baseurl}}/assets/img/{{ site.author_logo }}" class="author-profile-img"> -->
                <h4 class="card-title">{{ post.title }}</h4>
                <h6 class="card-subtitle mb-2" style="{{post.color}}; text-align: center; border-radius: 50px 0px; margin: 5px">{{ post.type }}</h6>
                <hr>
                <h6 class="card-subtitle mb-2 text-muted">{{ post.date | date: "%b %-d, %Y" }}</h6>
                <p class="card-text">{{ post.summary }} </p>

                <div class="post-categories" style="vertical-align:bottom">
                    {% if post %} {% assign categories = post.categories %} {% else %} {%
                    assign categories = page.categories %} {% endif %} {% for
                    category in categories %}
                    <a href="{{site.baseurl}}/blog/categories/{{category|slugize}}" class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline">{{category | capitalize}}</a>
                    {% unless forloop.last %}&nbsp;{% endunless %} {% endfor %}
                </div>
            </div>
            <hr>
            <a href="{{ post.url | prepend: site.baseurl }}" data-disqus-identifier="{{ post.url }}" class="btn btn-dark btn-lg" style="vertical-align:bottom; border-radius: 20px">Read</a>
        </div>
	{% endfor %}
</div>

