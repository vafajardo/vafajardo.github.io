---
layout: page
title:  fp_scala
---
<ul class="post-list">
	{% for post in site.categories.fpscala %}
	<li>
		<span>{{ post.date | date: "%b %d, %Y" }}</span>
		<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
	</li>
	{% endfor %}
</ul>