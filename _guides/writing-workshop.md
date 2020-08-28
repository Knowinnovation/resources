---
title: Writing Workshop
layout: default
homePage: true
includeAll: 
- writing-workshop-guide
includeIn: 
language:
- en-gb
---
## Welcome to the Writing Workshop Guide

This guide is designed to provide you with much of the information you need to run a Writing Workshop - including the [History of Knowinnovation Workshops](ideas_lab_guides/History of Knowinnovation Workshops), and [Articles From Previous Workshops](ideas_lab_guides/Articles From Previous Workshops) 

We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organising Committee pathway.
<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>