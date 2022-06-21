---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

This page is under construction! :-)

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Head TA

{% assign headta = site.staffers | where: 'role', 'Head TA' %}
{% for staffer in headta %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


## Readers

{% assign readers = site.staffers | where: 'role', 'Reader' %}
{% for staffer in readers %}
{{ staffer }}
{% endfor %}


# Credits for this course
The syllabus, lecture slides, web content, and assignments of this course are only the most recent iterations of a long history of HCI classes. This iteration of the course, at the very least, draws from prior course materials by Nate Weinmann, Janaki Vivrekar, Sarah Sterman, Andrew Head, Amy Pavel, Cesar Torres, Björn Hartmann, Eric Paulos, Valkyrie Savage, Maneesh Agrawala, Scott Klemmer, John Canny, and James Landay.