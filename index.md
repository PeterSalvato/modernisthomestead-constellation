---
layout: default
title: Modernist Homestead
---

# MODERNIST HOMESTEAD
**Biological Logistics & Land Systems**

This is a working documentation of homesteading operations: garden systems, livestock management, land rehabilitation, and the applied science of small-scale agriculture.

---

## Recent Posts

{% for post in site.posts limit:5 %}
  {% include post-card.html
     title=post.title
     url=post.url
     date=post.date
     excerpt=post.excerpt %}
{% endfor %}

[View Archive →](/archive/)
