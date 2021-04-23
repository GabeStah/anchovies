---
data:
  boss: '[Gorechop](https://www.wowhead.com/npc=162317/gorechop)'
  smash: '[Tenderizing Smash](https://www.wowhead.com/spell=318406/tenderizing-smash)'
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
requirement: Defeat Gorechop after tenderizing 2 hunks of meat with Tenderizing Smash in the Theater of Pain on Mythic difficulty.
title: '[Fresh Meat](https://www.wowhead.com/achievement=14607/fresh-meat)'
type: Group
zone: '[Theater of Pain](https://www.wowhead.com/zone=12841)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- There are (2) piles of meat in the room; one in the front-left corner and one in the back-right corner.
- If {{ data.boss }} is within a few yards of a meat pile while casting {{ data.smash }} the pile will break apart.

## Strategy

1. The tank moves {{ data.boss }} to (1) of the two meat piles.

!> The tank will likely have to momentarily step into the dangerous outside ring to get {{ data.boss }} close enough to the pile.

2. Wait for [Tenderizing Smash](https://www.wowhead.com/spell=318406/tenderizing-smash).
3. Move {{ data.boss }} to the other meat pile.
4. Wait for a second [Tenderizing Smash](https://www.wowhead.com/spell=318406/tenderizing-smash).
5. Kill {{ data.boss }}.
