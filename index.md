---
layout: default
---

# Ben Lubar's Non-Judgemental Fractal Guide for Complete Idiots

*Working Draft*

## Fractals

{% for fractal in site.fractals %}
- [{{ fractal.title }}]({{fractal.url}}){% endfor %}

## Mechanics

{% for mechanic in site.mechanics %}
- [{{ mechanic.title }}]({{mechanic.url}}){% endfor %}
