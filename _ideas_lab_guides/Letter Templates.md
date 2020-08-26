---
title: Letter Templates
layout: default
includeAll: letters
includeIn: administrator
language:
- en-gb
- en-us
---

Here you will find a collection of letter templates that can be personalized and sent out to your Director, Mentors, Speakers, Selection Panel, and Applicants. Please be sure to update these letters with the appropriate information (event title, dates, and responsibilities) that reflects the specifics of your event.

<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>