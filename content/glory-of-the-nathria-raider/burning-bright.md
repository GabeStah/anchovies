---
data:
  blazing_surge: '[Blazing Surge](https://www.wowhead.com/spell=329518/blazing-surge)'
  boss: "[Kael'thas](https://www.wowhead.com/guides/sun-kings-salvation-kaelthas-sunstrider-castle-nathria-raid-strategy-guide)"
  ember_blast: '[Ember Blast](https://www.wowhead.com/spell=325877/ember-blast)'
  fiery_strike: '[Fiery Strike](https://www.wowhead.com/spell=326455/fiery-strike)'
  phoenix: '[Reborn Phoenix](https://www.wowhead.com/npc=168962/reborn-phoenix)'
  shade: "[Shade of Kael'thas](https://www.wowhead.com/npc=165805/shade-of-kaelthas)"
  smoldering: '[Smoldering Remnants](https://www.wowhead.com/spell=328579/smoldering-remnants)'
  brazier:
    blazing: '[Blazing Brazier: Red (back-right)](https://www.wowhead.com/spell=329518/blazing-surge)'
    embered: '[Embered Brazier: Purple (front-right)](https://www.wowhead.com/spell=325877/ember-blast)'
    fiery: '[Fiery Brazier: Green (back-right)](https://www.wowhead.com/spell=326455/fiery-strike)'
    smoldering: '[Smoldering Brazier: Blue (front-right)](https://www.wowhead.com/spell=328579/smoldering-remnants)'
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
requirement: Redeem Kael'thas after lighting all four of the room's braziers in Castle Nathria on Normal difficulty or higher.
title: '[Burning Bright](https://www.wowhead.com/achievement=14608/burning-bright)'
video: https://www.youtube.com/watch?v=2vhRIhHJQqI&list=PLEimyKsVBkYBOZLXtjOV8TTwM6qqY7elm&index=6
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.moderate.style }}">{{ difficulty.moderate.name }}</span>**
> - Video: [YouTube]({{ video }})

## Details

- There are four braziers around the corners of the room: Fiery, Blazing, Embered, and Smoldering Braziers.
- Each brazier must be hit during the {{ data.shade }} phase by an ability corresponding to its name:
  - {{ data.brazier.blazing }}
  - {{ data.brazier.embered }}
  - {{ data.brazier.fiery }}
  - {{ data.brazier.smoldering }}
- Once all four braziers are activated the achievement turns white and {{ data.boss }} can be killed as normal.

## Preparation

- Use an extra healer for safety.
- Raid-mark all braziers with a corresponding color, rotating clockwise from the front-left entrance of the room: blue, green, red, purple.

```
G              BOSS               R






B            ENTRANCE             P
```

## Strategy

1. Engage {{ data.boss }} and fight as normal until the {{ data.shade }} spawns.
2. Non-tank raiders move toward {{ data.brazier.embered }}. Stack on the brazier for {{ data.ember_blast }} to activate it.
3. Tank moves {{ data.shade }} and stands on {{ data.brazier.blazing }}. Wait for {{ data.blazing_surge }} to activate brazier.
4. Raid moves toward {{ data.brazier.smoldering }}, pulls/pushes a {{ data.phoenix }} on top of it and kills it to ensure {{ data.brazier.smoldering }} activates.
5. Meanwhile, tank moves {{ data.shade }} to {{ data.brazier.fiery }} and waits for it to activate.
6. Confirm that the achievement is white then kill {{ data.shade }} and finish the fight as normal.
