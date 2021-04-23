---
data:
  boss: '[Surgeon Stitchflesh](https://www.wowhead.com/npc=166882/surgeon-stitchflesh)'
  meat_hook: '[Meat Hook](https://www.wowhead.com/spell=322681/meat-hook)'
  spare_parts: '[Spare Parts](https://www.wowhead.com/npc=171463/spare-parts)'
difficulty:
  very_easy:
    style: 'color: lightgreen;'
    name: Very Easy
  easy:
    style: 'color: green;'
    name: Easy
  moderate:
    style: 'color: yellow;'
    name: Moderate
  hard:
    style: 'color: red;'
    name: Hard
  very_hard:
    style: 'color: darkred;'
    name: Very Hard
requirement: Defeat Surgeon Stitchflesh after destroying two barrels of spare parts in the Necrotic Wake on Mythic difficulty.
title: "[Surgeon's Supplies](https://www.wowhead.com/achievement=14320/surgeons-supplies)"
type: Group
zone: '[The Necrotic Wake](https://www.wowhead.com/the-necrotic-wake)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.easy.style }}">{{ difficulty.easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- Around the room are small barrels of {{ data.spare_parts }}.
- Causing a Construct to {{ data.meat_hook }} a {{ data.spare_parts }} barrel destroys it.
- Just as with {{ data.boss }}, a {{ data.meat_hook }} can be aimed toward a {{ data.spare_parts }} barrel then sidestepped.

## Strategy

1. Engage {{ data.boss }} but hold DPS to avoid killing him too soon.
2. Hook (2) {{ data.spare_parts }} barrels with {{ data.meat_hook }}.
3. Confirm the {{ title }} achievement has white-status then kill {{ data.boss }}.
