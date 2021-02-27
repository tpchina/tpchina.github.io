---
layout: page
permalink: /itp/hardware_verification/
title: 硬件验证
class: itp
enable_right: true
categories: [COQ, ACL2]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>

{% bibliography -f hardware -q @*[category={{c}}]%}

{% endfor %}
</div>