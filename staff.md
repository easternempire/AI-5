---
layout: page
title: Staff / Contact
description: A listing of all the course staff members.
nav_order: 5
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

{% assign support_instructors = site.staffers | where: 'role', 'Support Instructor' %}
{% assign num_support_instructors = support_instructors | size %}
{% if num_support_instructors != 0 %}

{% assign teaching_headtf = site.staffers | where: 'role', 'Head TF' %}
{% assign num_teaching_headtf = teaching_headtf | size %}
{% if num_teaching_headtf != 0 %}

## Support Instructors

{% for staffer in support_instructors %}
{{ staffer }}
{% endfor %}
{% endif %}

## Contact 
For administrative or logistical questions, please e-mail class Helpline at [anshikagupta.work.email@gmail.com](mailto:anshikagupta.work.email@gmail.com) 


## Course Staff
{% for staffer in teaching_headtf %}
{{ staffer }}
{% endfor %}
{% endif %}

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


