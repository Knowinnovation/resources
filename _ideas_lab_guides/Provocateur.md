---
title: Provocateur
layout: default
includeAll: provocateurs
homePage: true
---

Thank you for agreeing to be a Provocateur at the upcoming workshop! Bringing people together and asking them to talk with each other from the viewpoints of their different disciplines is the first step to getting new perspectives on a challenge. Adding Provocateurs, or speakers, to the mix helps to deepen the overall understanding of the challenge.  Although each event is different, the Provocateur's role usually includes:
* Giving a short presentation at the workshop, usually up to 20 minutes.
* Challenging current ways of thinking.
* Introducing controversial perspectives.
* Inspiring new viewpoints.

These pages are designed to introduce you to the process and highlight the specific aspects of your role.
{%- for each in site.ideas_lab_guides -%}

{% if each.includeIn == "provocateurs" then %}

* [{{each.title}}]({{each.url}})

{% endif %}

{%- endfor -%}