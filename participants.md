---
title: Participants
includeAll: participants
---
# Preparing Participants

This section outlines the various preparatory activities that might be useful for the participants

{% for each in site.ideas_lab_guides %}

{% if each.includeIn == "participants" then %}

* [{{each.title}}]({{each.title}})

{% endif %}

{% endfor %}