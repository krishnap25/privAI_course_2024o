---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Weekly Schedule

The course will run in Slot J.
The Monday session will usually be a lab (please bring your laptops),
while the Wednesday/Thursday sessions will be a lecture. Both are in CRC 205.

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
