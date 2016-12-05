---
assignees:
- thockin

---

COMMON TEXT BEFORE

{% assign paths = page.url | split: "/" %}
{% if paths[2] == 'v1.4' %}
TIM: foo v1.4
{% elsif paths[2] == 'v1.3' %}
TIM: foo v1.3
{% else %}
TIM: foo dunno
{% endif %}

COMMON TEXT AFTER
