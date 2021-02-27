---
layout: page
permalink: /itp/math/
title: 形式化数学
class: itp
enable_right: true
categories: [大规模验证,验证框架,数学分析,代数,概率论,集合论和数理逻辑,其他高等数学,应用数学]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f math -q @*[category={{c}}]%}

{% endfor %}
</div>
