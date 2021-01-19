---
layout: page
permalink: /readings/
title: Readings
description: Readings about theorem proving.
---
### Official
{% for items in site.data.assistants.official%}
* <a class="page-link" href="{{items.link}}"> {{items.name}} </a>
{% endfor %}

### Tutorials/Books

{% for item in site.data.assistants.books_tutorials%}
#### {{item.name}}
{% for reading in item.readings%}
{% if reading.authors %}
* {{reading.authors}}: <a class="page-link" href="{{reading.url}}">{{reading.name}}</a>
{% else %}
* <a class="page-link" href="{{reading.url}}">{{reading.name}}</a>
{% endif %}
{% endfor %}
{% endfor %}

### Courses
{% for course in site.data.assistants.courses %}
* <a class="page-link" href="{{course.url}}">{{course.name}}</a>
{% endfor %}

### Websites
{% for site in site.data.assistants.websites %}
* <a class="page-link" href="{{site.url}}">{{site.name}}</a>
{% endfor %}

### Groups
{% for group in site.data.assistants.groups%}
* <a class="page-link" href="{{group.url}}">{{group.name}}</a>
{% endfor %}

### Competitions
{% for competition in site.data.assistants.competitions%}
* <a class="page-link" href="{{competition.url}}">{{competition.name}}</a>
{% endfor %}

### Papers
{% for paper in site.data.assistants.papers%}
* "{{paper.name}}." [PDF]({{paper.url}})<br />
{{paper.authors}},<br />
{{paper.conf}}
{% endfor %}



