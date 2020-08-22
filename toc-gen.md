---
layout: default
title: toc-gen.md
---
<h2>Table of Contents generator</h2> 
<ol>
{% for each in site.ideas_lab_guides %}
<li><a href="{{each.url}}">{{ each.title}}</a></li>

{% endfor %}
</ol>