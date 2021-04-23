---
data:
  add: '[Grisly Colossus](https://www.wowhead.com/npc=171095/grisly-colossus)'
  boss: '[Amarth](https://www.wowhead.com/npc=163157/amarth)'
  final_harvest: '[Final Harvest](https://www.wowhead.com/spell=321247/final-harvest)'
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
requirement: Defeat Amarth <The Harvester> after he"s consumed the corpse of a Grisly Colossus using Final Harvest in the Necrotic Wake on Mythic difficulty.
title: '[Bountiful Harvest](https://www.wowhead.com/achievement=14295/bountiful-harvest)'
type: Group
zone: '[The Necrotic Wake](https://www.wowhead.com/the-necrotic-wake)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.moderate.style }}">{{ difficulty.moderate.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- The back-left cubby of the room has a clickable Curio.
- Clicking the Curio spawns a {{ data.add }}.
- When {{ data.boss }} casts {{ data.final_harvest }} it does ~30% damage to the {{ data.add }}.
- If {{ data.final_harvest }} gets the killing blow the achievement credit is triggered.
- In case of emergency the Curio respawns when the encounter resets.

## Strategy

1. Tank clicks Curio to spawn {{ data.add }}.
2. Group DPSes the {{ data.add }} to ~20% then stops.
3. Tank engages {{ data.boss }}.
4. Fight proceeds as normal until {{ data.boss }} casts {{ data.final_harvest }} which should finish off the {{ data.add }}.
5. Confirm achievement is white-status and kill {{ data.boss }} as normal.
