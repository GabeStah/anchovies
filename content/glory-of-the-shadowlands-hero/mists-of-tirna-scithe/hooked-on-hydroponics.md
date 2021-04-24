---
data:
  boss: '[Ingra Maloch](https://www.wowhead.com/npc=164567/ingra-maloch)'
  droman: '[Droman Oulfarran](https://www.wowhead.com/npc=164804/droman-oulfarran)'
  hydra: '[Overgrown Hydra](https://www.wowhead.com/npc=172992/overgrown-hydra)'
  seed: '[Hydra Seed](https://www.wowhead.com/npc=172995/hydra-seed)'
  tears: '[Tears of the Forest](https://www.wowhead.com/spell=323177/tears-of-the-forest)'
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
requirement: Defeat Ingra Maloch after defeating an Overgrown Hydra in the Mists of Tirna Scithe on Mythic difficulty.
title: '[Hooked On Hydroponics](https://www.wowhead.com/achievement=14503/hooked-on-hydroponics)'
type: Group
zone: '[Mists of Tirna Scithe](https://www.wowhead.com/zone=13334)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.moderate.style }}">{{ difficulty.moderate.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Prerequisites

!> You **MUST** have a Night Fae-aligned player in your party to open the wall for this achievement.

## Details

- Behind root wall to the left of {{ data.boss }}'s room you'll find {{ data.seed }}.
- The {{ data.seed }} can be placed on the ground.
- During the {{ data.boss }} encounter {{ data.droman }}'s {{ data.tears }} ability splashes blue pools on the ground.
- If a {{ data.tears }} pool hits a placed {{ data.seed }} it gains a debuff stack.
- When a placed {{ data.seed }} reaches `9` stacks an {{ data.hydra }} spawns.

## Preparation

Clear the two trash packs between the seed room and {{ data.boss }}.

## Strategy

1. Engage {{ data.boss }} and DPS as normal.
2. Place {{ data.seed }} the boss.
3. Stack most of the group on top of/near the placed {{ data.seed }}
4. Wait for {{ data.droman }} to cast {{ data.tears }} and try to "aim" pool hits onto the {{ data.seed }}.
5. Push through another phase and repeat steps 3-4 until the {{ data.seed }} reaches 9+ stacks and the {{ data.hydra }} spawns.
6. Kill the {{ data.hydra }}.
7. Finish {{ data.boss }}.

!> Depending on group DPS be careful not to "kill" {{ data.droman }} during his phase too early. However, the longer he lives the more abilities {{ data.boss }} will use, so balance accordingly.
