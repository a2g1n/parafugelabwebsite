---
title: Blog
nav:
  order: 5
  tooltip: Mentions, moments and musings
---

# {% include headicons.html icon="fa-solid fa-feather-pointed" %}Blog

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
