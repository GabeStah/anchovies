---
data:
  boss: '[Globgrog](https://www.wowhead.com/npc=164255/globgrog)'
  appetizer: '[Finger Food](https://www.wowhead.com/npc=171474/finger-food)'
  entree: '[Hearty Haunch](https://www.wowhead.com/npc=172093/hearty-haunch)'
  dessert: '[Dissectible Dessert](https://www.wowhead.com/npc=172094/dissectible-dessert)'
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
    style: 'color: darkred;'
    name: Very Hard
requirement: Defeat Globgrog after feeding him a three course meal in Plaguefall on Mythic difficulty.
title: '[Full Gores Meal](https://www.wowhead.com/achievement=14347/full-gores-meal)'
type: Group
zone: '[Plaguefall](https://www.wowhead.com/zone=13228)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_easy.style }}">{{ difficulty.very_easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- Each "course" is a stationary neutral mob that spawns around the outside edges of the room.
- Moving {{ data.boss }} into melee range of a course mob consumes it.
- {{ data.boss }} will heal when consuming a course, so DPS is unnecessary prior to consuming all courses.
- The **Appetizer** is a slime named {{ data.appetizer }}, located in the front-left of the room and is active at the start of the fight.
- The **Entree** is named {{ data.entree }}, located in the back-left of the room and spawns after {{ data.appetizer }} is consumed.
- The **Dessert** is named {{ data.dessert }}, located in the back-right of the room and spawns after {{ data.entree }} is consumed.
- Tracking the achievement will indicate when each of the three courses are consumed.
- The tank will be taking relatively heavy damage while positioning within range of a slime.
  - The tank should try to stand on walls outside of slime while waiting for {{ data.boss }} to move.

## Strategy

1. Tank pulls {{ data.boss }} to the {{ data.appetizer }} on engagement at front-left and waits for it to be consumed.
2. DPS focuses on killing the small slimes that spawn throughout the fight.
3. Tank moves {{ data.boss }} to {{ data.entree }} at back-left.
4. Tank moves {{ data.boss }} to {{ data.dessert }} at back-right.
5. Kill the {{ data.boss }}.
