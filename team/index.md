---
title: Team
nav:
  order: 4
  tooltip: Meet our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="group == 'pi'" %}

{% include section.html %}

## Current Members

{% include list.html data="members" component="portrait" filter="group == 'current'" %}

{% include section.html %}

## Previous Members

{% include list.html data="members" component="portrait" filter="group == 'previous'" %}
