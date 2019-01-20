---
layout: page
title: Schedule
---

{% assign repo-base = "https://github.com/datascienceforall/dsfa-2018sp-public" %}
{% assign repo = repo-base | append: "/blob/master" %}

The links below will enable you to view the last year's slides and demos as well as the assignment notebooks
in your browser.  If you'd like to edit and execute the notebooks yourself, 
follow [these instructions]({{repo-base}}) to install the course software and 
download all the notebooks onto your own computer.

<table>
 <tbody>
  {% for event in site.data.schedule %}
  <tr>
    {% if event.type == 'unit' %}
    	<td markdown="span" colspan="4" class="unit"><b>{{ event.name }}</b></td>
    {% else %}
		<td markdown="span"><b>{{ event.topic }}</b>
		<br/>
			{% if event.num == 'guest' %}
				Lecture:
				[Slides](lec/{{event.slides}}), 
			{% elsif event.num %}
				Lecture: 
				[Slides](lec/lec{{event.num}}.pdf), 
				{% if event.no_demo %}
				{% else %}
					[Demo]({{repo}}/lectures/lec{{event.num}}.ipynb)
				{% endif %}
				<br/>
				{% if event.reading %}
				Reading: {{ event.reading }}
				{% endif %}
			{% endif %}
		</td>
		<td markdown="span">
			[{{event.assignment}}]({{repo}}/assignments/{{event.assignment}}/{{event.assignment}}.ipynb)
		</td>
	{% endif %}
  </tr>
  {% endfor %}
 </tbody>
</table>
