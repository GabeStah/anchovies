---
data:
  blooming: '[Bouquet of Blooming Sanguine Roses](https://www.wowhead.com/spell=339574/bouquet-of-blooming-sanguine-roses)'
  boss: '[Stone Legion General](https://www.wowhead.com/guides/stone-legion-generals-castle-nathria-raid-strategy-guide)'
  orb: '[Anima Orb](https://www.wowhead.com/spell=332393/anima-orb)'
  wilted: '[Bouquet of Wilted Sanguine Roses](https://www.wowhead.com/spell=339565/bouquet-of-wilted-sanguine-roses)'
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
requirement: Defeat the Stone Legion Generals while all players are carrying a Bouquet of Blooming Sanguine Roses in Castle Nathria on Normal difficulty or higher.
title: '[Feed Me, Seymour!](https://www.wowhead.com/achievement=14525/feed-me-seymour)'
video: https://www.youtube.com/watch?v=u5YV0PLRqgY&list=PLEimyKsVBkYBOZLXtjOV8TTwM6qqY7elm&index=9
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_hard.style }}">{{ difficulty.very_hard.name }}</span>**
> - Video: [YouTube]({{ video }})

## Details

- A clickable {{ data.wilted }} sits just outside the boss room.
- Clicking {{ data.wilted }} applies a (hidden) 10 minute buff.
- Collecting a {{ data.orb }} while carrying {{ data.wilted }} converts them to {{ data.blooming }}.
- When everyone in the raid has {{ data.blooming }} the achievement turns white and the boss is killable.
- Dying while carrying {{ data.wilted }} **FAILS** the achievement and the fight must be reset to try again.
- However, dying while carrying {{ data.blooming }} **DOES NOT** fail the achievement for the group, but it _may_ not give credit to the dead player.

_TLDR: In general, the fight should be reset if anyone dies that has not already converted to {{ data.blooming }}._

## Preparation

- Use one or two extra healers.
- Before engaging, have the raid stand near the {{ data.wilted }} but **DO NOT** click them.
- Once the 20-second pull timer begins everyone should click {{ data.wilted }} to gain the buff, then run into the room to engage.

## Strategy

1. After collecting {{ data.wilted }}, engage and fight {{ data.boss }} as normal.
2. Stop DPS during orb phase.
3. Everyone in the raid should collect an one **single** {{ data.orb }}, but **DO NOT** turn it in.
4. The longer this phase can be prolonged, the more {{ data.orb }}s can be collected.
5. Once everyone in the raid has converted to {{ data.blooming }}, confirm the achievement is white and proceed as normal.
6. If necessary, stop DPS and do not turn in {{ data.orb }}s during the second orb phase.
7. Once the achievement is white during the final phase, bloodlust and kill {{ data.boss }}.
