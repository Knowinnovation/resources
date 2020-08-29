---
title: Selection Panel
layout: default
includeAll: selection
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---
Thank you for agreeing to be on the Selection Panel for the upcoming workshop! A Knowinnovation workshop succeeds – or fails – primarily because of the right mix of people: Participants who represent a diverse range of experiences and who are likely to enjoy this intense, interdisciplinary experience. Choosing the Participants is done by Selection Panel early in the planning process, prior to the event. These Panel members are responsible for putting the right people in the room, and that is extremely important. 

These pages are designed to introduce you to the process and highlight the specific aspects of your role.
<ul>
{%- for each in site.ideas_lab -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>