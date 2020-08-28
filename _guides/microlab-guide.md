---
title: Microlab
layout: default
homePage: true
includeAll: microlabguide
includeIn: 
language:
- en-gb
- en-us
---
## Welcome to the Microlab Guide

This guide is designed to provide you with much of the information you need to run a Microlab 

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