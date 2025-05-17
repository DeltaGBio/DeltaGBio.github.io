---
title: Pipelines
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Pipelines

We integrates protein language models with mutation data to detect clinically relevant variations. It involves data preprocessing, mutation mapping, model inference to predict mutation impact, and result interpretation, providing actionable insights for personalized cancer treatment.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="pipelines" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="pipelines" filter="!group" style="small" %}
