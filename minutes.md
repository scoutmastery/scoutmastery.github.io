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

<center><a href="assets/ScoutmastersMinute.iba"><img src="assets/Get_it_on_iBooks_Badge_US_1114.svg"></a><a href="assets/ScoutmastersMinute.pdf" class="AdobeBuffer"><img src="assets/pdficon_large.png"></a>
<br />
<br />
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">The Scoutmaster's Minute</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://scoutmastery.com/minutes" rel="dct:source">http://scoutmastery.com/minutes</a>.
</center>
