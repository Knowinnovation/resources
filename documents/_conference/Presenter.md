---
title: Presenter
layout: default
includeAll: presenters
homePage: true
mode:
- f2f
- virtual
language:
- en-gb
- en-us
---

Thank you for agreeing to present at the event.

The following pages are designed to help you create and upload your presentation.

<ul>
{%- for each in site.ideas_lab -%}

{% for item in each.includeIn %}

{% if item == page.includeAll %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>