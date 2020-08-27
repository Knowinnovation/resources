---
title: Sandpit
layout: default
homePage: true
includeAll: 
- sandpit-guide
includeIn: 
language:
- en-gb
---
## Welcome to the Sandpit Guide

This guide is designed to provide you with much of the information you need to run a Sandpit - including the [History of Knowinnovation Workshops](ideas_lab_guides/History of Knowinnovation Workshops), and [Articles From Previous Workshops](ideas_lab_guides/Articles From Previous Workshops) 

We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organising Committee pathway.
<ul>
{%- for each in site.ideas_lab_guides -%}
{% if each.includeIn == {{page.includeAll}} then %}
<li><a href="{{each.url}}">{{each.title}}</a></li>
{% endif %}
{%- endfor -%}
</ul>