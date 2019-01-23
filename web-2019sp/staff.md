---
layout: page
title: Staff
---

All staff are listed in alphabetical order by role.

* * *

## Professors

<div class="container">
  {% for prof in site.data.profs %}
  <figure>
    <img src="pics/{{ prof.pic }}" height="200px" width="200px"/>
    <figcaption>
      <b>{{ prof.name }}</b><br/>
      {{ prof.email }}<br/>
	  {{ prof.office }}<br/>
    </figcaption>
  </figure>
  {% endfor %}
</div>

* * *

## PhD Teaching Assistants

<div class="container">
  {% for ta in site.data.phd_tas %}
  <figure>
    <img src="pics/{{ ta.pic }}" height="200px"  width="200px"/>
    <figcaption>
      <b>{{ ta.name }}</b><br/>
      {{ ta.netid }}, {{ ta.office }}<br/>
      Field: {{ ta.field }}<br/>
      <i>Ask me about: {{ ta.ama }}</i>
    </figcaption>
  </figure>
  {% endfor %}
</div>

* * *

## Undergraduate and Masters Teaching Assistants

<div class="container">
  {% for ta in site.data.tas %}
  <figure>
    <img src="pics/{{ ta.pic }}" height="200px"  width="200px"/>
    <figcaption>
      <b>{{ ta.name }}</b><br/>
      {{ ta.netid }}<br/>
      Major: {{ ta.major }}<br/>
      <i>Ask me about: {{ ta.ama }}</i>
    </figcaption>
  </figure>
  {% endfor %}
</div>

