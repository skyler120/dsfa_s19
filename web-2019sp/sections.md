---
layout: page
title: Sections
---

<table>
  <tr>
    <th>Section</th>
    <th>Time</th>
    <th>Room</th>
    <th>TA</th>
  </tr>
  {% for sect in site.data.sections %}
  <tr>
  	<td>DIS {{sect.section}}</td>
  	<td>{{sect.time}}</td>
  	<td>{{sect.room}}</td>
  	<td>{{sect.tas}}</td>
  </tr>
  {% endfor %}
</table>