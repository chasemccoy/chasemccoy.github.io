---
layout: default
permalink: /galleries/
---

<ul>
{% for post in site.galleries %}
	<li><a href="{{ post.url | remove:'/index.html'}}">{{ post.title }}</a></li>
{% endfor %}
</ul>