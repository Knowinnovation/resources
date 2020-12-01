---
title: Letter Templates
layout: default

includeAll: letters
includeIn: administrator
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---

Here you will find a collection of letter templates that can be adapted, and sent out to your Director, Mentors, Speakers, Selection Panel, and Applicants. Please be sure to update these letters with the appropriate information (event title, dates, and responsibilities) that reflects the specifics of your event.




<ul>
{%- for each in site.virtual_ideas_lab -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

<li><a href="{{each.url}}">{{each.title}}</a></li>




{% endif %}

{% endfor %}

{%- endfor -%}
</ul>