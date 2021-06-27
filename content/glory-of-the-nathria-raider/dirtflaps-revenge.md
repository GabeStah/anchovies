---
data:
  boss: '[Sludgefist](https://www.wowhead.com/npc=174733/sludgefist)'
  npc: '[Dirtflap](https://www.wowhead.com/npc=174073/dirtflap)
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
requirement: Defeat Sludgefist after he collides with pillars in Dirtflap's preferred order in Castle Nathria on Normal difficulty or higher.
title: "[Dirtflap's Revenge](https://www.wowhead.com/achievement=14294/dirtflaps-revenge)"
video: https://www.youtube.com/watch?v=e2e3_Ag9Bdc&list=PLEimyKsVBkYBOZLXtjOV8TTwM6qqY7elm&index=8
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Video: [YouTube]({{ video }})

## Details

- {{ data.npc }}, a friendly NPC, stands on top of a single pillar in {{ data.boss }}'s room.
- {{ data.npc }} moves to a new pillar after the previous one is shattered.
- Shattering all four pillars in the order {{ data.npc }} chooses turns the achievement white.

## Preparation

- Before engaging, have a tank run to the end of the right-hand corridor and talk to {{ data.npc }}.
- Once {{ data.npc }} moves into {{ data.boss }}'s room he'll stand on top of a pillar.
- Put a raid marker on {{ data.npc }}.

## Strategy

1. Engage {{ data.boss }} as normal.
2. Move {{ data.boss }} such that he can be charged into the current pillar where {{ data.npc }} is standing.
3. Stop DPS at ~25%.
4. Repeat step 2 until all pillars are destroyed and the achievement turns white.
5. Kill {{ data.boss }}
