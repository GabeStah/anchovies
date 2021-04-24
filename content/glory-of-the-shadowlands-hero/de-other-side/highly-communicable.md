---
data:
  blood: '[Corrupted Blood](https://www.wowhead.com/spell=322746/corrupted-blood)'
  boss: 'All Bosses'
  hakkar: '[Hakkar the Soulflayer](https://www.wowhead.com/npc=166473/hakkar-the-soulflayer)'
  manastorms: '[The Manastorms](https://www.wowhead.com/npc=101976/millificent-manastorm)'
  dealer: "[Dealer Xy'exa](https://www.wowhead.com/npc=164450/dealer-xyexa)"
  muehzala: "[Mueh'zala](https://www.wowhead.com/npc=169769/muehzala)"
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
requirement: Defeat Hakkar, the Manastorms, Dealer Xy'exa, and Mueh'zala while at least one party member is afflicted with Corrupted Blood within a single visit to in De Other Side on Mythic difficulty.
title: '[Highly Communicable](https://www.wowhead.com/achievement=14354/highly-communicable)'
type: Group
zone: '[De Other Side](https://www.wowhead.com/zone=13309)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_hard.style }}">{{ difficulty.very_hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- {{ data.blood }} lasts for `12` seconds and ticks every `3` seconds.
- {{ data.blood }} spreads to other party members within `7` yards on every tick.
- The achievement requirements are _only_ for boss kills, not trash in between.
- Eating food while out of combat allows {{ data.blood }}-afflicted players to heal.

## General Tips

- **ALWAYS** refresh to a full 12-second {{ data.blood }}-duration prior to using any mid-zone transport/portals.
- Sidecar-style mounts allow players to continue transferring {{ data.blood }} while moving outdoors.
  - Riding a Druid in mount form also works.

## Preparation

!> Clear **ALL** trash within the zone before engaging {{ data.hakkar }} to begin the achievement.

> Use `2` healers if possible since all {{ data.blood }}-afflicted players will take `586` DPS from the DoT.

- Assign `3` people to be the **Blood Group** -- These people will constantly maintain {{ data.blood }} throughout clear.
- While only `2` people are required, using `3` ensures a bit of redundancy in the case of a mistake or bug.

> Suggested players for the **Blood Group** are healers and ranged DPS capable of self-healing (e.g. Boomkin, Ele Shaman, Shadow Priest).

## Strategy

1. Engage {{ data.hakkar }}.

> Ensure the **Blood Group** players are stacked together and obtain {{ data.blood }} prior to killing {{ data.hakkar }}.

2. A healer and `1` other **Blood Group** member should always form a pair when traveling via mounts. Use a sidecar mount at all times.
3. Go to Mechagon.
4. Engage and kill {{ data.manastorms }}.
5. Go to Ardenweald.
6. Engage and kill {{ data.dealer }}.
7. For {{ data.muehzala }}, split the group into two separate portal groups, each with `1` **Blood Group** healer and (1-2) other to separate portals.
8. Engage {{ data.muehzala }} and kill `2` assigned portal adds/totems.
9. Repeat for remaining `2` portal adds/totems.
10. Finish {{ data.muehzala }} as normal.
