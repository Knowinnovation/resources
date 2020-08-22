---
title: Participants
includeAll: participants
layout: default
---
# Preparing Participants for the event

This section outlines the various preparatory activities that might be useful for the participants

{%- for each in site.ideas_lab_guides -%}

{% if each.includeIn == "participants" then %}

* [{{each.title}}]({{each.url}})

{% endif %}

{%- endfor -%}