---
title: Participants
includeAll: participants
homePage: true
layout: default
mode:
- virtual
language:
- en-gb
- en-us
---
# Preparing Participants for the event

This section outlines the various preparatory activities that might be useful for the participants

{%- for each in site.poster_session -%}

{% if each.includeIn == page.includeAll %}

* {{each.title}}]({{each.url}})

{% endif %}

{%- endfor -%}