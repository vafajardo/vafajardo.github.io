---
layout: page
title:  reinforcement_learning
---
<ul class="post-list">
	{% for post in site.categories.rl %}
	<li>
		<span>{{ post.date | date: "%b %d, %Y" }}</span>
		<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
	</li>
	{% endfor %}
</ul>
