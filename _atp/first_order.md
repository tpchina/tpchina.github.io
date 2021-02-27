---
layout: page
permalink: /atp/first_order/
title: 一阶逻辑求解
class: atp
enable_right: true
categories: [概述, 系统介绍,算法验证,高阶逻辑的扩展,机器学习引导证明]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f first_order -q @*[category={{c}}]%}

{% endfor %}
</div>
