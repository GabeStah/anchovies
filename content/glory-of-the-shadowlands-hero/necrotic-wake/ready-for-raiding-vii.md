---
data:
  blizzard: '[Blizzard](https://www.wowhead.com/spell=287294/blizzard)'
  boss: '[Nalthor the Rimebinder](https://www.wowhead.com/npc=166945/nalthor-the-rimebinder)'
  comet_storm: '[Comet Storm](https://www.wowhead.com/spell=320784/comet-storm)'
  dark_exile: '[Dark Exile](https://www.wowhead.com/spell=321894/dark-exile)'
  frozen_binds: '[Frozen Binds](https://www.wowhead.com/spell=320788/frozen-binds)'
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
requirement: Defeat Nalthor the Rimebinder without being struck by Comet Storm, Blizzard, or the secondary effect of Frozen Binds in the Necrotic Wake on Mythic difficulty.
title: '[Ready for Raiding VII](https://www.wowhead.com/achievement=14285/ready-for-raiding-vii)'
type: Personal
zone: '[The Necrotic Wake](https://www.wowhead.com/the-necrotic-wake)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.moderate.style }}">{{ difficulty.moderate.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- DPS: {{ data.blizzard }} is cast frequently in the downstairs "gauntlet" and must be dodged by the DPS player sent below.
- All: {{ data.comet_storm }} is channeled on every group member in a quick series at the player"s location ~1 second previously. Move quickly to avoid.
- Healer: {{ data.frozen_binds }} is cast on a random player and triggers an explosion upon dispel.

## Planning

The faster the boss dies the less chance for failure, so wait for all DPS cooldowns prior to engagement.

## Strategy

Engage {{ data.boss }} as normal.

### {{ data.frozen_binds }}

To avoid {{ data.frozen_binds }} make sure you are not within the area of effect during dispel. This is largely up to the healer to properly time dispels.

!> It is possible to preemptively cast [Blessing of Freedom](https://www.wowhead.com/spell=1044/blessing-of-freedom) (or similar abilities) on the player targeted by {{ data.boss }} before {{ data.frozen_binds }} is applied which will negate the initial application.

### {{ data.blizzard }}

The DPS player ported downstairs via {{ data.dark_exile }} should move slowly and methodically through the gauntlet to avoid {{ data.blizzard }} casts. Teleportation and movement-speed abilities are particularly useful.

### {{ data.comet_storm }}

The entire group should prepare for {{ data.comet_storm }} and plan a personal movement pattern that doesn"t overlap other effects.

!> If your group has a lot of melee you can stack up in front on the tank prior to {{ data.comet_storm }}, then all move in tandem in the same direction around the boss.
