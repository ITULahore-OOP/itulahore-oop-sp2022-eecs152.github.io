---
layout: page
title: Schedule
nav_order: 3
description: The weekly event schedule.
---

# Ramadan Weekly Schedule
{% assign schedules = site.schedules | where: 'role', 'Ramadan' %}
{% for schedule in schedules %}
{{ schedule }}
{% endfor %}

# Regular Weekly Schedule
{% assign schedules = site.schedules | where: 'role', 'Regular' %}
{% for schedule in schedules %}
{{ schedule }}
{% endfor %}

[Book UBS Appointment](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZiRUdjc0dwUzZhfGRlZmF1bHR8ZmIxOGMwNGJhNjA4YTNhN2I2MDZlNzAxNzU0NWRlNGQ){: .btn .btn-outline .h6}
[Book TA Appointment](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUVYbzM5MTRRQlh4fGRlZmF1bHR8OTFlZDZiZDI5M2EyNWVlN2U0NGEzNjlhZGIzM2RiN2E){: .btn .btn-outline .h6}