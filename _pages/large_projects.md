---
layout: page
permalink: /large_projects/
title: Projects
---

{% for item in site.data.projects.projects%}
* <a class="page-link" href="{{item.url}}">{{item.name}}</a>
{% endfor %}
