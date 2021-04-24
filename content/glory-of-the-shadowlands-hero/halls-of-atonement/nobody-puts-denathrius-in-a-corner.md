---
data:
  boss: '[Lord Chamberlain](https://www.wowhead.com/npc=164218/lord-chamberlain)'
  pull: "[Chamberlain's Chorus](https://www.wowhead.com/spell=341245/chamberlains-chorus)"
  toss: '[Telekinetic Toss](https://www.wowhead.com/spell=323143/telekinetic-toss)'
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
requirement: Defeat Lord Chamberlain with 3 Sinstone Statues in corners of the room in the Halls of Atonement on Mythic difficulty.
title: '[Nobody Puts Denathrius in a Corner](https://www.wowhead.com/achievement=14352/nobody-puts-denathrius-in-a-corner)'
type: Group
zone: '[Halls of Atonement](https://www.wowhead.com/zone=12831)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.hard.style }}">{{ difficulty.hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- During the {{ data.boss }} encounter the boss frequently throws a statue at the current location of a random non-tank party member via {{ data.toss }}.
- Twice during the encounter, at 70% and 40% HP, {{ data.boss }} will teleport to the center of the room and suck in and push away all statues via {{ data.pull }}.
- The achievement requires that you kill {{ data.boss }} while **at least** `3` statues are "in corners" of the room.

> When using {{ data.toss }}, {{ data.boss }} _seems_ to prefer targeting statues that are nearest to his location. This can be used to your advantage when positioning statues for the achievement.

## Preparation

Before engaging {{ data.boss }} move into the far left area of the room and place ground raid markers at the `4` corners in this area.

!> Shift-click to track the {{ title }} achievement. It is critical to know that the statues are considered "in place" prior to getting the killing blow on {{ data.boss }}, lest you fail and have to reset the dungeon to try again.

## Strategy

1. Pull {{ data.boss }} and DPS him as normal.
2. Keep fighting until {{ data.boss }} is below `40%` and _after_ the second {{ data.pull }} phase ends.
3. At this point, get {{ data.boss }} down to ~10% HP then halt all DPS.
4. Simultaneously, move the entire party over to the left side of the room with the markers.
5. Each non-tank player should stand directly in the corner under a unique marker.
6. The tank should try to keep {{ data.boss }} near the _furthest_ statue out in the room (i.e. not in an assigned corner).
7. When {{ data.toss }} is cast it will target the current location of a random non-tank player.
8. After a statue lands within a marked corner position, the player(s) that were at that marker should move to a different marked corner that _does not_ have a statue occupying it.
9. Repeat steps 7-8 until at least `3` statues are in marked corner positions.
10. Confirm that the achievement status is successful/white, indicating the statues are "in corners."
11. Quickly kill {{ data.boss }} before the next {{ data.toss }} cast.

!> If group DPS is weak and/or some members are dead, save and use Bloodlust and other DPS cooldowns for the final 10% burn on {{ data.boss }}. Alternatively, keep moving and tossing statues into "free" corners, which wil guarantee you always have `3` statues in corners. While doing this, you can slowly get {{ data.boss }} down to 1%, then wait for the final {{ data.toss }} and push for the kill.
