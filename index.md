---
layout: page
title: Welcome to ScoutMastery 
tagline: A place for scouters and scout things
---
{% include JB/setup %}

## What is this site?


    
## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

