---
title: Sandpit
layout: default
mode:
- f2f
- virtual
language:
- en-gb
---
## Welcome to the Sandpit Guide

This guide is designed to provide you with much of the information you need to run a Sandpit - including the [History of Knowinnovation Workshops](ideas_lab/History of Knowinnovation Workshops), [Articles From Previous Workshops](ideas_lab/Articles From Previous Workshops), and [NSF-funded Ideas Lab policies](https://www.nsf.gov/pubs/policydocs/pappguide/nsf16001/nsf16_1.pdf#page#54). 

We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organizing Committee pathway.


<ul>
{%- for each in site.sandpit -%}

{% if {{page.homePage}}==true then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>