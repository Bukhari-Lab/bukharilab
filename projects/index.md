---
title: Projects
nav:
  order: 3
  tooltip: Research projects and tools
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="semantic web, data integration, clinical prediction, medical imaging" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
