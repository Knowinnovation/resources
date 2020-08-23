---
title: index
layout: default
---
## Welcome to the Resources Wiki

Here you will find all of the information you need to run a workshop with Knowinnovation - including the [History of Knowinnovation Workshops](ideas_lab_guides/History of Knowinnovation Workshops), [Articles From Previous Workshops](ideas_lab_guides/Articles From Previous Workshops), and [NSF-funded Ideas Lab policies](https://www.nsf.gov/pubs/policydocs/pappguide/nsf16001/nsf16_1.pdf#page#54). 

We have organized the resources into "pathways". Each pathway is designed to meet the needs of a particular role in the event. You are most welcome to explore all the documents, but if you are short of time, then please start with the pathway that seems most relevant for you.

temp

{%- for each in site.ideas_lab_guides -%}
   {% if each.homePage == true then %}
      * [{{each.title}}]({{each.url}})
   {% endif %}
{%- endfor -%}


