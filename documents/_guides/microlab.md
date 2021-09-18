---
title: Microlabs
layout: default
includeAll: microlab
---
{% assign all_docs = site.shared | concat: site.microlab  %}

## Welcome to the Microlab Guide

This guide is designed to provide you with much of the information you need to run a Microlab Session. We have organised the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. If you are not sure about your role, it is probably best to start with the Organizing Committee pathway.

### Pathways with subdirectories
<ul>
{%- for each in site.microlab.pathways -%}

	{% for item in each.includeIn %}

		{% if each.homePage ==true and item == page.includeAll %}

		<li><a href="{{each.url}}">{{each.title}}</a></li>

		{% endif %}

	{%- endfor -%}

{%- endfor -%}
</ul>


### Pathways
<ul>
{%- for each in all_docs -%}

	{% for item in each.includeIn %}

		{% if each.homePage ==true and item == page.includeAll %}

		<li><a href="{{each.url}}">{{each.title}}</a></li>

		{% endif %}

	{%- endfor -%}

{%- endfor -%}
</ul>


### Additional Reading
<ul>
{%- for each in site.shared -%}

{% if each.homePage==true %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>

### Full Set Reading
<ul>
{%- for each in all_docs -%}

{% if each.homePage==true %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{%- endfor -%}
</ul>