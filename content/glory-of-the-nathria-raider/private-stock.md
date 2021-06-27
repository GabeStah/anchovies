---
data:
  alter_time: '[Alter Time](https://www.wowhead.com/spell=108978/alter-time)'
  anima:
    ard: 'Ardenweald Anima (Blue)'
    mal: 'Maldraxxus Anima (Green)'
    maw: 'Maw Anima (Purple)'
  boss: "[Artificer Xy'mox](https://www.wowhead.com/npc=166644/artificer-xymox)"
  tear: '[Dimensional Tear](https://www.wowhead.com/spell=328437/dimensional-tear)'
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
requirement: Defeat Artificer Xy'mox after returning loose Maldraxxus, Ardenweald, and Maw Anima to their display cases in Castle Nathria on Normal difficulty or higher.
title: '[Private Stock](https://www.wowhead.com/achievement=14617/private-stock)'
video: https://www.youtube.com/watch?v=Uv8FRNXIl6Q&list=PLEimyKsVBkYBOZLXtjOV8TTwM6qqY7elm&index=5
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.easy.style }}">{{ difficulty.easy.name }}</span>** - **<span style="{{ difficulty.hard.style }}">{{ difficulty.hard.name }}</span>**
> - Video: [YouTube]({{ video }})

## Details

- Three anima orbs are sitting {{ data.boss }}'s room (see [this map](https://www.wowhead.com/maps?data=13224.2:619385685385694449)): {{ data.anima.mal }}, {{ data.anima.ard }}, and {{ data.anima.maw }}.
- One anima orb is pulled to a position on the ground at shortly after engagement and each major phase of the fight.
- Clicking on a loose anima orb completely stuns the holding player.
- Meanwhile, a colored ring appears some distance away from the corresponding orb. The ring color matches the orb.
- Moving an active anima orb into its matching deposit ring gives credit for that orb.
- Once all three orbs are correctly deposited the achievement turns white.

## Preparation

- Pick up all three anima orbs before entering the room/engaging {{ data.boss }}. It **DOES NOT** matter who picks up the original orbs.

## Normal Strategy (Hard)

1. Engage {{ data.boss }} as normal.
2. 10-15 seconds in the {{ data.anima.mal }} activates.
3. Raid mark the anima orb location and the deposit ring location.
4. An assigned player clicks {{ data.anima.mal }} and become stunned.
5. The next two players afflicted by {{ data.tear }} drop the teleport positions at the anima orb/stunned player location and at the corresponding ring location.
6. The {{ data.anima.mal }} carrier is automatically teleported and deposits the orb.
7. Repeat steps 2-6 for the next two anima orb spawns (one shortly after phase 2 and one shortly after phase 3).
8. Confirm the achievement is white and kill {{ data.boss }} as normal.

## Mage Strategy (Easy)

1. Engage {{ data.boss }} as normal.
2. 10-15 seconds in the {{ data.anima.mal }} activates.
3. Raid mark the anima orb location and the deposit ring location.
4. A single, assigned Mage stands directly on top of the deposit ring.
5. The Mage casts {{ data.alter_time }} then runs over and clicks the {{ data.anima.mal }}.
6. {{ data.alter_time }} will teleport the carrying Mage back to the deposit ring location and place the orb.
7. Repeat steps 2-6 in each phase, with the same or a different assigned Mage.
8. Confirm the achievement is white and kill {{ data.boss }} as normal.
