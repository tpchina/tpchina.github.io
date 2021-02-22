---
layout: page
permalink: /atp/sat/
title: SAT求解
class: atp
enable_right: true
categories: [概述, 并行求解, 证明检验]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f sat -q @*[category={{c}}]%}

{% endfor %}
</div>