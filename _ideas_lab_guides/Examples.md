---
title: Examples
layout: default
includeAll: examples
includeIn:
- director
- organizer
- mentor
language:
- en-gb
- en-us
---

## Examples of projects that were created at previous events

<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>