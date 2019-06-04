---
title: 'test page'
---

```
{% if config.plugins.blogroll.enabled %}
  <aside class="widget widget_meta">
    <h2 class="widget-title">{{'SIDE PROJECTS'|t}}</h2>
    {% include 'partials/blogroll.html.twig' with {'tags': ['projects']} %}
  </aside>
{% endif %}

```