---
title: Letter Templates
layout: default
includeAll: letters
includeIn: administrator
language:
- en-gb
- en-us
---

Here you will find a collection of letter templates that can be personalized and sent out to your Director, Mentors, Speakers, Selection Panel, and Applicants. Please be sure to update these letters with the appropriate information (event title, dates, and responsibilities) that reflects the specifics of your event.

Director
 - [Letter To Director](Letter to Director)

Mentors
 - [Letter To Mentors](Letter to Mentors)

Provocateurs
 - [Letter To Provocateurs](Letter to Provocateurs)
 - [Letter To Plus Ten Speakers](Letter to Plus 10 Speakers)

Selection Panel
 - [Letter to Selection Panel](Letter to Selection Panel)

 Applicants
 - [Application Received](Application Received Letter)
 - [Acceptance Letter](Acceptance Letter)
 - [FourSight Invitation](Letter Foursight)
 - [Rejection Letter](Rejection Letter)
 - [Waitlist Letter](Waitlist Letter)
 - [RSVP Confirmation: Will Attend](RSVP Confirmation Letter)

<ul>
{%- for each in site.ideas_lab_guides -%}

{% for item in each.includeIn %}

{% if item == {{page.includeAll}} then %}

<li><a href="{{each.url}}">{{each.title}}</a></li>

{% endif %}

{% endfor %}

{%- endfor -%}
</ul>