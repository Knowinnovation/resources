---
title: Participants
includeAll: participants
layout: default
language:
- en-gb
- en-us
---
# Preparing Participants for the event

This section outlines the various preparatory activities that might be useful for the participants

{%- for each in site.ideas_lab_guides -%}

{% if each.includeIn == {{page.includeAll}} then %}

* [{{each.title}}]({{each.url}})

{% endif %}

{%- endfor -%}