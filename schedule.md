---
layout: page
title: Schedule
description: The weekly event schedule.
---



<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23cae5e6&ctz=America%2FLos_Angeles&showNav=1&showCalendars=0&showPrint=0&showTabs=1&title=CS160%20Summer%202022%20Course%20Calendar&mode=WEEK&src=Y19nN2Y5cjBiNDZqbXUxNnJxbG92N2llN29xa0Bncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23009688" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Weekly Schedule


{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}