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
