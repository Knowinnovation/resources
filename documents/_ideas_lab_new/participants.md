---
title: Participants
includeAll: participants
includeIn:
- ideaslabguide
layout: default
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---
# Preparing Participants for the event

This section outlines the various preparatory activities that might be useful for the participants

{%- for each in site.ideas_lab -%}

{% for item in each.includeIn %}

{% if item.includeIn == page.includeAll %}

* {{each.title}}]({{each.url}})

{% endif %}
{% endfor %}

{%- endfor -%}