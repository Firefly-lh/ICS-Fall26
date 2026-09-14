---
layout: page
title: Schedule
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
Peking University, 2026 Fall
{: .mb-0 .fs-6 .text-grey-dk-000 }

<p>
<a href="https://xlab.pku.edu.cn/" class="btn btn-green">XLab</a>
<a href="https://autolab.pku-ics.com/" class="btn btn-green">AutoLab</a>
<a href="https://missing.lcpu.dev/" class="btn btn-green">Getting Started</a>
<a href="https://firefly-lh.github.io/ICS-Fall26-Slides/1" class="btn btn-green">Slides</a>
</p>

## Schedule
{% for module in site.modules %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}