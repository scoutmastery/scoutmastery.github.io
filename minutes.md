---
layout: page
title: "New Page"
description: ""
---
{% include JB/setup %}
{% for post in site.categories["minute"] %}
<li><a href="{{ BASE_PATH }}{{node.url}}">{{node.title}}</a></li>
{% endfor %}
