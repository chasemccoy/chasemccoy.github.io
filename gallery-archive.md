---
layout: default
permalink: /galleries/
---

<ul>
{% for post in site.galleries %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>