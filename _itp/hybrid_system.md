---
layout: page
permalink: /itp/hybrid_system/
title: 混成系统验证
class: itp
enable_right: true
categories: [dL/KeYmaera, HCSP/HHL]
---
{% include sidebar.html %}

<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>

{% bibliography -f hybrid -q @*[category={{c}}]%}

{% endfor %}
</div>