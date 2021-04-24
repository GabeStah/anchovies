---
data:
  add: '[Shard of Halkias](https://www.wowhead.com/npc=164557/shard-of-halkias)'
  beam: '[Refracted Sinlight](https://www.wowhead.com/spell=322913/refracted-sinlight)'
  boss: '[Halkias](https://www.wowhead.com/npc=165408/halkias)'
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
requirement: Defeat Halkias after he reabsorbs all three Shards of Halkias in the Halls of Atonement on Mythic difficulty.
title: '[Picking Up the Pieces](https://www.wowhead.com/achievement=14567/picking-up-the-pieces)'
type: Group
zone: '[Halls of Atonement](https://www.wowhead.com/zone=12831)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.easy.style }}">{{ difficulty.easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- Each of the (3) platforms on which {{ data.add }} initially stand are "special" zones.
- Moving {{ data.boss }} within `20` yards of the initial spawn point of a {{ data.add }} triggers a large red Anima Explosion on {{ data.boss }}.
- Triggering all (3) Anima Explosions in a single attempt enables the achievement credit.

## Preparation

Kill **ALL** trash mobs including {{ data.add }} that connect pathways between {{ data.boss }} and each of the {{ data.add }} platforms.

> It is highly suggested to use (2) healers during this achievement, as _most_ of the time is spent running around and dodging {{ data.beam }}s.

## Strategy

1. Pull {{ data.boss }} to the bottom-level {{ data.add }} platform.
2. Ensure {{ data.boss }} gets close enough to trigger the large red Anima Explosion graphic.
3. Move {{ data.boss }} to the top-left {{ data.add }} platform next and wait for the Anima Explosion.
4. Move {{ data.boss }} to the top-right {{ data.add }} platform and wait for the Anima Explosion.
5. Kill {{ data.boss }}.

!> The most dangerous part of this achievement is when the boss reaches 100 energy and casts {{ data.beam }}. Be weary of his energy level and your positioning while the group is kiting around. Technically, only the tank and possibly a single healer need to actually kite the boss around the room, since you do not need to kill him until all (3) absorbs are complete.
