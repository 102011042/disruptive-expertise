---
title: Disruptive Expertise
layout: base
header-image: "/assets/images/book-to-network.png"
header-title: Disruptive Expertise
header-subtitle: When technology questions authority
header-position: 35% center
---

## Who's an expert?
When a new technology changes how information is produced, what happens to authority and expertise?

From the printing press to the telegraph to social media, new information technologies have triggered the same anxious debates: Who gets to be an authority now? Can we trust what we're reading? How do we know what we know?

These essays, written by students in HIST 300 at the University of New Mexico, explore that recurring disruption. Each one examines a historical moment when a technology upended the authority of expertise — and asks what it might mean for understanding AI today.

The writing here was researched and produced with AI assistance, and documents that process honestly. History doesn't give us simple answers about technology. But it helps us ask better questions.



{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-stack.html cards=cards %}

