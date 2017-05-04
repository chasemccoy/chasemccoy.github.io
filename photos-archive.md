---
permalink: "/photos/"
layout: default
---

{% for post in site.photos %}
<a href="{{ post.url | remove:'/index.html'}}" class="button">{{ post.title }}</a>
{% endfor %}