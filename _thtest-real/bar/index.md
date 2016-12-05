---
assignees:
- thockin

---

COMMON TEXT BEFORE

{% assign paths = page.url | split: "/" %}
{% if paths[2] == 'v1.4' %}
TIM: bar v1.4
{% elsif paths[2] == 'v1.3' %}
TIM: bar v1.3
{% else %}
TIM: bar dunno
{% endif %}

COMMON TEXT AFTER
