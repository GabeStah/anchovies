---
data:
  boss: '[Sire Denathrius](https://www.wowhead.com/guides/sire-denathrius-castle-nathria-raid-strategy-guide)'
  burden: '[Burden of Sin](https://www.wowhead.com/spell=326699/burden-of-sin)'
  cleansing_pain: '[Cleansing Pain](https://www.wowhead.com/spell=326707/cleansing-pain)'
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
requirement: Defeat Sire Denathrius after removing Burden of Sin from all players before March of the Penitent is cast in Castle Nathria on Normal difficulty or higher.
title: '[Clear Conscience](https://www.wowhead.com/achievement=14610/clear-conscience)'
video: https://www.youtube.com/watch?v=ya2BThOrIpM&list=PLEimyKsVBkYBOZLXtjOV8TTwM6qqY7elm&index=10
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Video: [YouTube]({{ video }})

## Details

- Everyone in the raid must clear **ALL** of their {{ data.burden }} stacks before entering phase 2.
- Without heavy cooldowns/healing, having the entire raid hit by {{ data.cleansing_pain }} while at the _same_ number of {{ data.burden }} stacks is dangerous.

## Preparation

- Add an extra healer.

## Strategy

1. Engage {{ data.boss }} as normal.
2. Halt DPS at ~80%, as we must wait for all six {{ data.cleansing_pain }} casts.
3. Use the following stacking order for {{ data.cleansing_pain }} casts:

---

1. Group A
2. Both Groups
3. Both Groups
4. Both Groups or anyone with 2+ {{ data.burden }} stacks
5. Group B or anyone with a remaining {{ data.burden }} stack

---

4. Confirm that nobody in the raid has any {{ data.burden }}.
5. Push {{ data.boss }} to 70% and then kill him as normal.
