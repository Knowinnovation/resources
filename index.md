---
title: index
layout: title-page

---
## Welcome to the Resources Wiki

We have organized the resources into a series of guides, based upon the type of event. You are most welcome to explore all the documents, but if you are short of time, then please start with the guide that seems most relevant for you.

aaa

{% for coll in site.collections %}
-  {{coll.label}}
{% endfor %}

guides loop first

{% for each in site.guides %}
* {{each.title}}
{% endfor %}

now for the ideas lab collection
{% for each in site.ideas_lab %}
* {{each.title}}
{% endfor %}



{{site.collections}}

------------
{{site.documents}}

-----------
{{page.dir}}