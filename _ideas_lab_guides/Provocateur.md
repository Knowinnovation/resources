---
title: Provocateur
layout: default
includeAll: provocateurs
includeIn:
- ideas-lab-guide
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---

Thank you for agreeing to be a Provocateur at the upcoming workshop! Bringing people together and asking them to talk with each other from the viewpoints of their different disciplines is the first step to getting new perspectives on a challenge. Adding Provocateurs, or speakers, to the mix helps to deepen the overall understanding of the challenge.  Although each event is different, the Provocateur's role usually includes:
* Giving a short presentation at the workshop, usually up to 20 minutes.
* Challenging current ways of thinking.
* Introducing controversial perspectives.
* Inspiring new viewpoints.

These pages are designed to introduce you to the process and highlight the specific aspects of your role.

<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>