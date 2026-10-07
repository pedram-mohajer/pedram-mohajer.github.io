---
layout: page
title: News
permalink: /news/
nav: false
---

{% for item in site.data.news %}
<div style="margin-bottom: 1.2rem; padding-bottom: 1.2rem; border-bottom: 1px solid var(--global-divider-color);">
  {{ item.text }}
</div>
{% endfor %}
