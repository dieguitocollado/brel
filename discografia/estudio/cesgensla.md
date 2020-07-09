---
layout: cesgensla
title: Ces Gens-Là
nav_order: 1
parent: Estudio
---
{% for post in site.categories.Cesgensla %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}