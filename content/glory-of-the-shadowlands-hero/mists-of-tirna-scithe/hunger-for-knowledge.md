---
data:
  add: '[Spinemaw Gorger](https://www.wowhead.com/npc=172312/spinemaw-gorger)'
  boss: "[Tred'ova](https://www.wowhead.com/npc=164517/tredova)"
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
    style: 'color: #da0000;'
    name: Very Hard
requirement: Defeat Tred'ova after defeating an Enlightened Spinemaw Gorger in the Mists of Tirna Scithe on Mythic difficulty.
title: '[Hunger for Knowledge](https://www.wowhead.com/achievement=14375/hunger-for-knowledge)'
type: Group
zone: '[Mists of Tirna Scithe](https://www.wowhead.com/zone=13334)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- Some of the trash around {{ data.boss }} contains {{ data.add }}s.
- Pulling a {{ data.add }} next to {{ data.boss }} causes the boss to start to Consume the {{ data.add }}.

!> Stunning/interrupting the {{ data.add }} during the Consumption halts the process. The boss should be reset and a new {{ data.add }} pulled in to try again.

## Strategy

1. Clear trash leading up to {{ data.boss }} as normal.
2. CC at least (1) {{ data.add }} within the preceding packs.
3. Pull the {{ data.add }} next to {{ data.boss }}.
4. Patiently wait for the {{ data.add }} to become an **Enlightened** version.
5. Agro and kill the **Enlightened Spinemaw Gorger**.
6. Kill {{ data.boss }} as normal.
