---
layout: page
title: Schedule
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
Peking University, 2025 Fall
{: .mb-0 .fs-6 .text-grey-dk-000 }

<p>
<a href="http://162.105.31.232/" class="btn btn-purple">AutoLab</a>
<a href="https://clab.pku.edu.cn/" class="btn btn-blue">CLab</a>
<a href="https://missing.lcpu.dev/" class="btn btn-green">Getting Started</a>
<a href="https://ics.huh.moe/" class="btn btn-blue">Memos</a>
<a href="https://firefly-lh.github.io/ICS-Fall26-Slides/1" class="btn btn-green">Slides</a>
</p>

## Schedule
{% for module in site.modules %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}