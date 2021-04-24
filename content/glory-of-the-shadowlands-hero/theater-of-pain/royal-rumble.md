---
data:
  boss: '[Mordretha](https://www.wowhead.com/npc=165946/mordretha-the-endless-empress)'
  ghost: '[Ghostly Contender](https://www.wowhead.com/npc=173675/ghostly-contender)'
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
requirement: Defeat Mordretha, the Endless Empress, after performing a /challenge and defeating 2 Ghostly Contenders in the Theater of Pain on Mythic difficulty.
title: '[Royal Rumble](https://www.wowhead.com/achievement=14533/royal-rumble)'
type: Group
zone: '[Theater of Pain](https://www.wowhead.com/zone=12841)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.hard.style }}">{{ difficulty.hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- When {{ data.boss }} reaches 50% health `2` targetable {{ data.ghost }} mobs will appear in the crowd around the arena.
- Targeting a {{ data.ghost }} and typing `/challenge` activates the mob and makes them attackable.

> Any living {{ data.ghost }} will remain active and attackable if the group wipes or the fight is reset.

## Strategy

1. Attack {{ data.boss }} until it reaches 50%.
2. Target and `/challenge` a {{ data.ghost }}.
3. Kill the spawned {{ data.ghost }}.
4. Repeat steps 2 - 3 a second time.
5. Kill {{ data.boss }}.

!> The incoming tank damage can be quite high with the boss and 1-2 {{ data.ghost }} adds.
