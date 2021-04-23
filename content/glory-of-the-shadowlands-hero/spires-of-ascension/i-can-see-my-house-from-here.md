---
data:
  boss: '[Devos](https://www.wowhead.com/npc=167410/devos)'
  orb1front: 'Orb #1 (Front)'
  orb2left: 'Orb #2 (Left)'
  orb3middle: 'Orb #3 (Middle)'
  orb4right: 'Orb #4 (Right)'
  orb5back: 'Orb #5 (Back)'
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
requirement: Gather all five orbs within 60 seconds of each other in Spires of Ascension after defeating Devos, Paragon of Doubt in the Spires of Ascension on Mythic difficulty.
title: '[I Can See My House From Here](https://www.wowhead.com/achievement=14327/i-can-see-my-house-from-here)'
type: Group
zone: '[Spires of Ascension](https://www.wowhead.com/zone=12837)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.hard.style }}">{{ difficulty.hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

> This achievement can be attempted as many times as necessary within a given instance, so don't fret a couple failed attempts.

- (5) Orbs are floating around the dungeon, _far_ up in the sky.
- {{ data.orb1front }} is located directly out from the {{ data.boss }} platform.
- {{ data.orb2left }}, {{ data.orb3middle }}, and {{ data.orb4right }} are located above the central dungeon platforms, respective to their assigned direction name (see below):

![trio-orbs](https://i.imgur.com/ezJjxhW.jpg)

- {{ data.orb5back }} is located above the initial hallway platform shortly after zoning in.
- After defeating {{ data.boss }} a pair of clickable wings appears at the edge of the platform.
- Clicking the wings launches the player forward, _through_ {{ data.orb1front }} and provides a long-standing slowfall effect.
- After launching for a moment the player will be unable to control their facing/direction.
  - After a brief period, however, the player can turn and fly in their desired direction.

!> Reaching the central orbs and especially {{ data.orb5back }} requires immediate and explicit facing as soon as control is allowed after launching. Players should have a good idea where they should face and do so as soon as possible.

With proper facing the travel time to respective orbs after launching is:

| Orb                   | Travel Time (sec) |
| --------------------- | ----------------- |
| {{ data.orb1front }}  | 0                 |
| {{ data.orb2left }}   | 60                |
| {{ data.orb3middle }} | 55                |
| {{ data.orb4right }}  | 60                |
| {{ data.orb5back }}   | 110               |

Orbs also have a respawn time of `180` seconds.

!> It is necessary to stagger the pickup timing of particular Orbs given the respawn and travel time.

## Planning

Assign all (5) party members to a specific Orb. In general, the further away the Orb the more difficult it is to reach.

> {{ data.orb1front }} player must be capable of a personal slow-fall effect. This player will need to explicitly click off their wings buff after collecting {{ data.orb1front }}, and it is critical that this player does not die or the achievement will fail.

Once assignments are determined the party leader should create a custom macro with the following text, replacing `PlayerName` with each assigned name:

```
/dbm broadcast timer 70 PlayerName #5 Back
/dbm broadcast timer 120 PlayerName #2 Left
/dbm broadcast timer 120 PlayerName #4 Right
/dbm broadcast timer 125 PlayerName #3 Middle
/dbm broadcast timer 180 PlayerName #1 Respawn
```

This macro creates DBM timers that indicate when a given player should click the wings and launch toward their assigned orb.

## Strategy

> All party members should be ready to click the wings when their timer ends.

1. The {{ data.orb1front }} player clicks wings.
2. At the same moment the group leader clicks the timer macro. This indicates when each respective player should click the wings to launch and start flying toward their assigned Orb.
3. Meanwhile, the {{ data.orb1front }} player has collected their Orb and should manually click off the wings buff when it safe to do so. This player must slow-fall, bubble, or use some other ability to survive the fall.
4. The {{ data.orb1front }} player makes their way back up to the {{ data.boss }} platform and waits the `180` seconds for {{ data.orb1front }} to respawn.
5. All other assigned players will be in flight and collecting their Orbs around the time the {{ data.orb1front }} respawns.
6. The {{ data.orb1front }} player clicks the wings a second time to collect the Orb again, which should complete the achievement for the group.
