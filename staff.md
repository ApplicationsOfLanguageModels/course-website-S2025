---
layout: page
title: Staff
description: A listing of all the course support people
---

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign co_instructors = site.staffers | where: 'role', 'Co-Instructor' %}
{% assign num_co_instructors = co_instructors | size %}
{% if num_co_instructors != 0 %}
## Co-Instructors

{% for staffer in co_instructors %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
