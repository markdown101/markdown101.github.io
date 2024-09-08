---
layout: tools
title: 工具
description: 支持 Markdown 的应用程序和组件。
last_modified_at: 2021-12-04
---

<div class="row">
  {% for tool in site.tools %}
  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px; font-size: 20px;"><a href="{{ tool.url }}"><img src="/assets/images/tool-icons/{{ tool.icon }}" alt="{{ tool.title }} logo" style="width:50px; margin-top:-5px"></a>&nbsp;&nbsp;{{ tool.title }}</h4>
        <p class="card-text">{{ tool.description }}</p>
        <a href="{{ tool.url }}" class="btn btn-outline-secondary btn-sm">Learn more</a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
