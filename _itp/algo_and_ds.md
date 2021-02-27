---
layout: page
permalink: /itp/algo_and_ds/
title: 算法与数据结构
class: itp
enable_right: true
categories: [概述, 验证框架, 搜索和排序, 数据结构, 图论算法, 其它算法, 时间复杂度的验证, 随机算法的验证, 模拟检验算法的验证, 人工智能算法的验证]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f algo_and_ds -q @*[category={{c}}]%}

{% endfor %}
</div>