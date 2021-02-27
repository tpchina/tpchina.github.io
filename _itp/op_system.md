---
layout: page
permalink: /itp/op_system/
title: 操作系统验证
class: itp
enable_right: true
categories: [seL4, CertiKOS, 其它]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>

{% bibliography -f os -q @*[category={{c}}]%}

{% endfor %}
</div>