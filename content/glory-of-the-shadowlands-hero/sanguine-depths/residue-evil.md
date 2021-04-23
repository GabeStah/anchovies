---
data:
  add: '[Fleeting Manifestation](https://www.wowhead.com/npc=168882/fleeting-manifestation)'
  boss: '[Executor Tarvold](https://www.wowhead.com/npc=162103/executor-tarvold)'
  captive: '[Forlorn Captive](https://www.wowhead.com/npc=165073/forlorn-captive)'
  residue: '[Residue](https://www.wowhead.com/spell=323551/residue)'
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
requirement: Defeat Executor Tarvold after slaying 8 Forlorn Captives with the effects of Residue in Sanguine Depths on Mythic difficulty.
title: '[Residue Evil](https://www.wowhead.com/achievement=14286/residue-evil)'
type: Group
zone: '[Sanguine Depths](https://www.wowhead.com/zone=12842)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.moderate.style }}">{{ difficulty.moderate.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- There are a total of (8) non-aggressive, non-agroable {{ data.captive }} standing in jail cells around the circular arena.
- While fighting {{ data.boss }} the {{ data.add }} he spawns will drop {{ data.residue }} pools when killed.
  - The radius of the {{ data.residue }} pool is based on the _energy_ total the {{ data.add }} had when it died.
- Any {{ data.captive }} will typically die if it is within the radius of a {{ data.residue }} pool.
- Allowing a {{ data.add }} to reach 70+ energy before being killed creates a very large pool radius.
- If the {{ data.add }} is moved to the cell doorway prior to dying the pool can then reach any {{ data.captive }} standing on the inside.

## Planning

- Clear **ALL** aggressive trash in the entire ring area, including all mobs within jail cells, just to be safe and ensure no surprises during the achievement attempt.
- While doing so, use raid markers to indicate the cell locations that contain {{ data.captive }}.

!> It is **HIGHLY** recommended you use (2) healers for this achievement. There is no DPS requirement (just a lot of movement and waiting around), so survival is most important.

## Strategy

1. The tank agros {{ data.boss }} and pulls him to the first {{ data.captive }} cell door.
2. Wait for a {{ data.add }} to spawn and reach 70+ energy, then kill it next to the cell door.
3. The tank and most of the group should move around toward the next cell marker.
4. Meanwhile, one player can stay behind and confirm the {{ data.captive }} inside have perished.
5. Repeat until all (8) {{ data.captive }} are killed.
6. Finish {{ data.boss }} as normal.
