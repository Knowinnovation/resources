---
title: Ideas lab
layout: default
homePage: true
includeAll: 
- ideas-lab-guide
includeIn: 
language:
- en-gb
- en-us
---
## Welcome to the Ideas Lab Guide

This guide is designed to provide you with much of the information you need to run an Ideas Lab - including the [History of Knowinnovation Workshops](ideas_lab_guides/History of Knowinnovation Workshops), [Articles From Previous Workshops](ideas_lab_guides/Articles From Previous Workshops), and [NSF-funded Ideas Lab policies](https://www.nsf.gov/pubs/policydocs/pappguide/nsf16001/nsf16_1.pdf#page#54). 

We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organizing Committee pathway.
<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}



<li><a href="{{each.url}}">{{each.title}} - ({{item}}) - {{each.includeIn}} </a></li>



{% endfor %}

{%- endfor -%}
</ul>