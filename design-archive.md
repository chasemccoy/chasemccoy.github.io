---
permalink: "/design/"
layout: default
---

{% for post in site.design %}
<a href="{{ post.url | remove:'/index.html'}}" class="button">{{ post.title }}</a>
{% endfor %}