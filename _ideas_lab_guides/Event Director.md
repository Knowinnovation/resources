---
title: Director
layout: default
homePage: true
includeAll: director
---
Thank you for agreeing to take on the role of the Director at the upcoming workshop! Having a Director at an event gives participants a colleague to look to for guidance and perspective, who is also an expert in the field. Although each event is different, the Director’s role usually includes:
* Acting as the leader of the event.
* Guiding the process from a scientific content perspective.
* Setting the stage with a Call to Action, clarifying the vision up front, and steering the event to stay aligned with that vision over the course of the event. 

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