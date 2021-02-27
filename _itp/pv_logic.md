---
layout: page
permalink: /itp/pv_logic/
title: 程序验证逻辑
class: itp
enable_right: true
categories: [分离逻辑, 并发程序逻辑]
---
{% include sidebar.html %}

<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>

{% bibliography -f plv -q @*[category={{c}}]%}

{% endfor %}
</div>