---
data:
  add: '[Shattered Devastator](https://www.wowhead.com/npc=171456/shattered-devastator)'
  boss: '[Oryphrion](https://www.wowhead.com/npc=162060/oryphrion)'
  ordnance: '[Empyreal Ordnance](https://www.wowhead.com/spell=324444/empyreal-ordnance)'
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
requirement: Defeat Oryphrion after activating and destroying all three Shattered Devastators in the Spires of Ascension on Mythic difficulty.
title: '[Goliath Offline](https://www.wowhead.com/achievement=14331/goliath-offline)'
type: Group
zone: '[Spires of Ascension](https://www.wowhead.com/zone=12837)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- (3) inanimate {{ data.add }} are spread around the room.
- Blue Anima Fields spawn at player locations when {{ data.boss }} casts {{ data.ordnance }}.
- An individual {{ data.add }} is activated when hit by a {{ data.ordnance }} Animal Field.

!> A {{ data.add }} must be killed within `33` seconds of activation or it will deactivate.

## Planning

Clear all trash in the room.

## Strategy

With relatively weak group gear/DPS:

1. The tank pulls {{ data.boss }} toward {{ data.add }} #1.
2. The tank stands underneath {{ data.add }} #1 until {{ data.ordnance }} spawns an Anima Field under them.
3. After the Anima Field, move {{ data.boss }} out of Anima Field until {{ data.add }} #1 activates.
4. Kill {{ data.add }} #1.
5. Repeat steps for {{ data.add }} #2 and #3.
6. Kill {{ data.boss }}.

With strong group gear/DPS:

1. Have (1) non-tank player each preemptively stand underneath each {{ data.add }}.
2. Tank pulls {{ data.boss }} to front-center of room and awaits {{ data.ordnance }}.
3. Once Anima Fields spawn all (3) {{ data.add }} will activate.
4. Group up {{ data.add }} and burn them down.
5. Kill {{ data.boss }}.
