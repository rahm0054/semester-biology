---
layout: page
title: Laboratory Syllabus
catalog: BTEC 330
credits: 3
semester: Spring 2022
professor: Nandita Rahman (she/hers)
office: Zoom
email: rahm0054@umbc.edu
schedule: ['Lecture: Tuesdays, 3-4 pm ET, REMOTE', 'Lab: Thursday, 3-6 pm ET, In-Person']
location: "Lecture - Blackboard, Lab - Rm Shady Grove Building IV 5312"   
office_hours: "By Appointment"
office_hours_location: Zoom
 
---

## Course

{{ site.title }}
{{ page.catalog }}, {{ page.credits }} Credits, {{ page.semester }}

### Instructor

{{ page.professor }}
Office: {{ page.office }}
Email:
[{{ page.email }}](mailto:{{ page.email }})

### Times and Location

{% for class in page.schedule %}
  {{ class }}
{% endfor %}
{{page.location}}

### Office Hours

Times: {{ page.office_hours }}
Location: {{ page.office_hours_location }}

By appointment. *Note: my schedule gets very busy during the semester so
please try to schedule appointments as far in advance as possible. In general it
will be very difficult to set up appointments less than 24 hours in advance.*

### Website

The syllabus and other relevant class information and resources will be posted
on Blackboard, the laboratory information will be posted at [{{ site.url}}]({{ site.baseurl }}/). 

Changes to the schedule will be posted to our Blackboard site so please try to check it
periodically for updates.


### Course Communications
Email: [{{ page.email }}](mailto:{{ page.email }})
and Blackboard
