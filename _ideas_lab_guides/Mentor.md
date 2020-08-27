---
title: Mentor
layout: default
includeAll: mentor
includeIn:
- ideas-lab-guide
- mentor
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---
Thank you for agreeing to be a Mentor at the upcoming workshop! Mentors are similar to “peer reviewers” but with a much more creative role: to connect and catalyze. The Mentor team is usually a diverse group, providing expertise on various dimensions of the problem. Although each event is different, the Mentor role usually includes:
 * Encouraging new ideas by asking questions.
 * highlighting ideas that seem exciting. 
 * Making connections between participants and to the wider body of knowledge.
 * Assisting in funding recommendations.

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
