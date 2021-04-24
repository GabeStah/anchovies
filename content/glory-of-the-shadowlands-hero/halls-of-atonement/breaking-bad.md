---
data:
  add: '[Undying Stonefiend](https://www.wowhead.com/npc=164363/undying-stonefiend)'
  boss: '[Echelon](https://www.wowhead.com/npc=156827/echelon)'
  curse: '[Curse of Stone](https://www.wowhead.com/spell=319603/curse-of-stone)'
  leap: '[Stone Shattering Leap](https://www.wowhead.com/spell=319592/stone-shattering-leap)'
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
requirement: Defeat Echelon after shattering 18 or more Undying Stonefiends at one time in the Halls of Atonement on Mythic difficulty.
title: '[Breaking Bad](https://www.wowhead.com/achievement=14284/breaking-bad)'
type: Group
zone: '[Halls of Atonement](https://www.wowhead.com/zone=12831)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.hard.style }}">{{ difficulty.hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Prerequisite

!> It is **HIGHLY** recommended to have a curse dispel within the party to help movement for the {{ data.leap }}-targeted player.

## Details

- During a typical {{ data.boss }} kill a set of `6` {{ data.add }}s will spawn and be stacked, killed, and then destroyed by the next {{ data.leap }} cast.
- {{ data.leap }} will **ONLY** destroy "inactive" (i.e. statue-form) {{ data.add }}s that it hits.
- Only `6` {{ data.add }}s spawn per wave and the achievement requires killing `18` {{ data.add }}s at once, so multiple waves need to be stacked up without destroying them.

## Preparation

Shift-click the {{ title }} achievement to track it, so you can visually see when the `18` {{ data.add }} credit is applied. You won't _receive_ the achievement until {{ data.boss }} dies afterward, but watching for the achievement prerequisite to turn white indicates that you're clear to kill the boss.

!> Use (2) healers if possible, as there is _a lot_ of damage toward the ends of this achievement.

## Strategy

> Most of the time party members should be standing around the edges of the room to make it less likely to accidentally hit {{ data.add }}s with {{ data.leap }}.

1. Pull {{ data.boss }} as normal.
2. The moment {{ data.boss }} summons {{ data.add }}s the party should collapse toward the center of the room to gather {{ data.add }}s together.

Use knockbacks and interrupts to help gather mobs.

3. Spread out away from the {{ data.add }}s prior to {{ data.curse }} applications.
4. Existing {{ data.add }}s will reactivate during the next summon round.
5. Stack in the middle and kill both new and old {{ data.add }}s.
6. Repeat steps 2-5 until the **fourth** wave of {{ data.add }}s.

> Although the achievement only requires `18`, which is `3` full waves of {{ data.add }}s, it's best to wait for the extra wave to ensure the next {{ data.leap }} hits at least `18` destroyed {{ data.add }}s.

7. Use bloodlust/DPS cooldowns to kill all active {{ data.add }}s following this fourth wave.
8. This time everyone should **REMAIN** in the center during the next {{ data.curse }} application.
9. The {{ data.leap }}-afflicted player must centralize their position to ensure they hit at least `18` {{ data.add }}s.
10. Confirm that the tracked achievement is white/successful.
11. Finish the fight and kill {{ data.boss }} as normal.
