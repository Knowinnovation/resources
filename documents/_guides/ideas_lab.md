---
title: Ideas lab
layout: default
---
## Welcome to the Ideas Lab Guide

This guide is designed to provide you with much of the information you need to run an Ideas Lab. We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organizing Committee pathway.


<ul>
{%- for each in site.ideas_lab -%}

{% if each.homePage==true %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>