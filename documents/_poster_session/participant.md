---
title: Participants
layout: default
includeAll: participants
homePage: true
mode:
- virtual
language:
- en-gb
- en-us
---

This section outlines the various preparatory activities that might be useful for the participants

{%- for each in site.poster_session -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

* {{each.title}}]({{each.url}})

{% endif %}
{% endfor %}

{%- endfor -%}
