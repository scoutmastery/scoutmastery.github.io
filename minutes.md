---
layout: page
title: "Scoutmaster Minutes"
description: ""
---
{% include JB/setup %}

One of my [Woodbadge](http://www.woodbadge.org/Listings/current.php) tickets was to compile a list of _Scoutmaster's Minutes_ that could be used around the campfire. Specifically, my ticket also included publishing the compiled lessons in book form. As I compile more minutes, it is my goal to add them to the publications below.

{% for post in site.categories["scoutmasters minute"] %}
<li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<br />

<center><a href="assets/ScoutmastersMinute.iba"><img src="assets/Get_it_on_iBooks_Badge_US_1114.svg"></a><a href="assets/ScoutmastersMinute.pdf" class="AdobeBuffer"><img src="assets/pdficon_large.png"></a></center>