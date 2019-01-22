---
layout: page
title: Schedule
---

{% assign repo-base = "https://github.com/dsfa2019/public" %}
{% assign repo = repo-base | append: "/blob/master" %}
{% assign tb = "http://www.cs.cornell.edu/courses/cs1380/2018sp" %}

The links below will enable you to view the slides and demos as well as the assignment notebooks
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
				[Slides](lec/{{event.slides}})
			{% elsif event.num == 'none' %}
				{% if event.reading %}
					Reading: {{event.reading}}
				{% endif %}
			{% elsif event.num == 'class' %}
				Lecture: 
				[Slides](lec/{{event.slides}}.pdf), 
				{% if event.no_demo %}
				{% else %}
					[Demo]({{repo}}/lec/{{event.slides}}.ipynb)
				{% endif %}
				<br/>
				{% if event.reading %}
					Reading: {{event.reading}}
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
