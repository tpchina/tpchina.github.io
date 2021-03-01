---
layout: page
permalink: /atp/smt/
title: SMT求解
class: atp
enable_right: true
categories: [概述, 基本算法,Congruence Closure,理论判定算法,量词实例化,系统介绍,程序验证工具,证明重构,其它]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f smt -q @*[category={{c}}]%}

{% endfor %}
</div>
