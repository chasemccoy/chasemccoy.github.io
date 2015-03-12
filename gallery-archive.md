---
layout: default
permalink: /galleries/
---

{% for post in site.galleries %}
<a href="{{ post.url | remove:'/index.html'}}" class="button">{{ post.title }}</a>
{% endfor %}