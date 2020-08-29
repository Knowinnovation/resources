---
title: index
layout: title-page

---
## Welcome to the Resources Site

We have organized the resources into a series of guides, one per type of event. You are most welcome to explore all the documents, but if you are short of time, then please start with the guide that seems most relevant for you.

Guide List::

<ul>
{% for each in site.guides %}
<li><a href="{{each.url}}">{{each.title}}</a></li>
{% endfor %}
</ul>
