---
title: index
layout: title-page
---
## Welcome to the Resources Wiki

We have organized the resources into a series of guides, based upon the type of event. You are most welcome to explore all the documents, but if you are short of time, then please start with the guide that seems most relevant for you.

change to page again - and one more time - and back again
loop has gone

{{site.collections}}

about to start the loop
<ul>
{% for each in site.ideas_lab %}
inside the loop
{{ forloop.rindex }}

{% endfor %}
</ul>