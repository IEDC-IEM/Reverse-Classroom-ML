---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Instructors

{% assign instructors = site.staffers %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
