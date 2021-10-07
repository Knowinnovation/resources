---
title: Examples of projects that were created at previous events.
layout: default
includeAll: examples
includeIn:
- director
- organizer
- mentor
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---

## Examples of projects that were created at previous events

<ul>
{%- for each in site.ideas_lab -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>