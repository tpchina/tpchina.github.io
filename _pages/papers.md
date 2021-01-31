---
layout: about
permalink: papers
title: Papers
description:  Papers related to theorem proving
---

{% for conf in site.data.papers.confs %}
### {{conf.venue}}
{% if conf.selected %}
{% for c in conf.content %}
#### {{c.year}}
{% for title in c.titles %}
* "{{title.name}}. "[PDF]({{title.url}})<br />
{{title.authors}},<br />
{{title.booktitle}}
{% endfor %}
{% endfor %}
{% else %}
{% for y in conf.years%}
* [{{y.year}}]({{year.url}})
{% endfor %}
{% endif %}

{% endfor %}
