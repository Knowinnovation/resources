---
title: index
layout: default
---
## Welcome to the Resources Wiki

We have organized the resources into a series of guides, based upon the type of event. You are most welcome to explore all the documents, but if you are short of time, then please start with the guide that seems most relevant for you.
<ul>
{%- for each in site -%}
{% if each.homePage == true then %}
<li><a href="{{each.url}}">{{each.title}}</a></li>
{% endif %}
{%- endfor -%}
</ul>

