---
layout: home
title: Operating System Course Honor Track
nav_exclude: true
seo:
  type: Course
  name: Operating System Course Honor Track
---

# {{ site.tagline }}
{: .mb-2 }
2022 Spring, taught by [Xin Jin](https://xinjin.github.io/index.html)
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
