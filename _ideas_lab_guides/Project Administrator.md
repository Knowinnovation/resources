---
title: Project Administrator
layout: default
includeAll: administrator
includeIn:
- ideas-lab-guide
Language:
- en-gb
- en-us
---

Leading up to the event, having someone - often a member of the Organizing team - focused on administration and logistics is invaluable. When an event runs smoothly at an ideal venue, everyone is able to focus on novel science and making new connections. The Project Administrator’s role includes:
 * Coordinating and scheduling planning meetings.
 * Researching and securing a venue for the event.
 * Arranging travel and hotel accommodations for participants.
 * Working with the KI team to order the proper Equipment and Supplies
 * Collecting the materials for the hub group.
 * Communicating with applicants during the application review and invitation process.

In order to make things easier, we've included some resources that we hope you find useful. These pages are designed to introduce you to the process and highlight the specific aspects of your role.
<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>
