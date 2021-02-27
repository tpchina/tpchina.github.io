---
layout: page
permalink: /itp/block_chain/
title: 区块链验证
class: itp
enable_right: true
categories: [F*, Lem, K Framework, Isabelle, 其它]
---
{% include sidebar.html %}
<div class="publications">
{% for c in page.categories %}
<h2 class="year">{{c}}</h2>

{% bibliography -f blockchain -q @*[category={{c}}]%}

{% endfor %}
</div>