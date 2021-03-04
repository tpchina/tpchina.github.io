---
layout: page
permalink: /itp/history/
title: 概述和历史
class: itp
enable_right: true
categories: [概述]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f history -q @*[category={{c}}]%}

{% endfor %}
</div>
