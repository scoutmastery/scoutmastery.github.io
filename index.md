---
layout: page
title: Welcome to ScoutMastery!
tagline: A place for scouters and scout things
---
{% include JB/setup %}

## What is this site?

A blogger I follow talks about the **Magic of 7**, namely that

>"it takes hearing new information 7 times before it’s retained." 

In other words, what is found on this site is not necessarily new. In fact, this may be the _umpteenth_ time hearing what you've read. However, **it is the aim of the site to "do a good turn daily"** and to **"help other people at all times."**

If what you've found here is helpful, please feel free to pass it on.

    
## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Others I follow

<ul>
<li><a href="http://scoutmastercg.com" alt="Scoutmaster CG">Scoutmaster CG</a></li>
<li><a href="http://thescoutmasterminute.net/author/thescoutmasterminute/" alt="Scoutmaster Jerry's Blog">Scoutmaster Jerry</a></li>
</ul>
