---
layout: default
title: About
categories: ["jblog"]
---
# About page

This page tells you a little bit about me.
<br>
{{ site.url }},{{ site.baseurl }},{{ page.url }}
<br>
{{ page.url | prepend: site.baseurl | prepend: site.url }}
<br>
 {{site.title}}<br>
 {{page.title}}<br>
<br>
-------------------<br>
{% post_url 2018-08-20-bananas %}<br>
<br>
<br>
 {{site.baseurl}}<br>
 {{site.relative_url}}<br>