---
title: Organising Committee
layout: default
includeAll: organizer
includeIn:
- sandpit-guide
mode:
- f2f
- virtual
language:
- en-gb
---

The Organising Committee is usually made up of 2-4 individuals who initiate and oversee the execution of a workshop. Organisers usually include representatives from funding bodies and partners associated with event. Their main objectives are to understand the other roles within the workshop - specifically the Mentors and Director -  and recruit those individuals, as well as to set the question or overarching challenge of workshop.

Being on the Organising Committee should be an enjoyable experience. The fact that funding may be awarded at the end of the event is part of what creates the energy and momentum of the workshop experience. It's important - and useful - if one or two staff members from the hosting and funding organisation(s) are present at the event. 

There is plenty to do to kick off the event and having people to help with the administration and logistics is helpful. During the week, it's good to have the funding organisation represented, to track the development of the projects and to answer any questions about criteria for funding or how funding will be distributed.

These pages are designed to introduce you to the process and highlight the specific aspects of your role.

<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>