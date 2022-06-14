---
layout: gooCal
title: Google Calendar
description: Google Calendar!
---

<meta charset='utf-8' />
<link href='fullcalendar/main.css' rel='stylesheet' />
<script src='fullcalendar/main.js'></script>
<script>

	document.addEventListener('DOMContentLoaded', function() {
		var calendarEl = document.getElementById('calendar');
		var calendar = new FullCalendar.Calendar(calendarEl, {
			initialView: 'dayGridMonth'
		});
		calendar.render();
	});

</script>

