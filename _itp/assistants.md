---
layout: page
permalink: /itp/assistants/
title: 证明辅助工具
class: itp
enable_right: true
categories: [系统介绍,证明和策略语言,归纳和余归纳,用户界面]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>
{% bibliography -f assistants -q @*[category={{c}}]%}

{% endfor %}
</div>
