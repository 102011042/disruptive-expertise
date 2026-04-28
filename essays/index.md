---
title: Why We Need Print
layout: base
header-title: History Is Written by The Press
---

# Essays

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-stack.html cards=cards %}
