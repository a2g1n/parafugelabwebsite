---
title: Resources
nav:
  order: 3
  tooltip: Protocols, datasets and code
---

# {% include icon.html icon="fa-solid fa-wrench" %}Resources

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="protocols, dataset, code" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="resources" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="resources" filter="!group" style="small" %}

