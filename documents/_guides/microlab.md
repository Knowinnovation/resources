---
title: Microlabs
layout: default
---
## Welcome to the Microlab Guide

This guide is designed to provide you with much of the information you need to run a Microlab Session. We have organised the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organizing Committee pathway.

### General Reading
<ul>
{%- for each in site.shared -%}

{% if each.homePage==true %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>


### Specific Reading
<ul>
{%- for each in site.microlab -%}

{% if each.homePage==true %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>