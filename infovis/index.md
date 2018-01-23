---
layout: archive
title: "Tableau作品集"
date: 2018-1-2T11:40:45-04:00
modified:
excerpt: "作品集"
tags: []
image: 
  feature: 
---

- <a href="https://public.tableau.com/views/_16303/1_1?:embed=y&:display_count=yes&publish=yes/Dashboard1?:showVizHome%3Dno" target="_blank">![数据分析.png](https://i.loli.net/2018/01/23/5a6725f592046.png)</a>






<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->
