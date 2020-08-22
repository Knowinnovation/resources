---
layout: default
title: toc-gen.md
---

# this should be level 1

<h1>{{page.name}}</h1>
<h2>{{page.url}}</h2>
<h3>{{site.ideas_lab_guides}}</h3>

What follows should loop over the output. I will now try including the content.


{% for each in site.ideas_lab_guides %}
{{ forloop.rindex }}

{% endfor %}