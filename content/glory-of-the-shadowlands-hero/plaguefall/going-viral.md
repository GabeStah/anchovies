---
data:
  boss: '[Doctor Ickus](https://www.wowhead.com/npc=164967/doctor-ickus)'
  debuff: '[Volatile Coating](https://www.wowhead.com/spell=333178/volatile-coating)'
  vial: '[Volatile Substance](https://www.wowhead.com/spell=333162/volatile-substance)'
  volatile_bomb: '[Volatile Plague Bomb](https://www.wowhead.com/npc=174018/volatile-plague-bomb)'
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
requirement: Defeat Doctor Ickus after destroying 2 Volatile Plague Bombs in Plaguefall on Mythic difficulty.
title: '[Going Viral](https://www.wowhead.com/achievement=14296/going-viral)'
type: Group
zone: '[Plaguefall](https://www.wowhead.com/zone=13228)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.easy.style }}">{{ difficulty.easy.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- {{ data.boss }} jumps between all (4) side platforms prior to engagement.
- The table on the front-right platform has a clickable {{ data.vial }} vial.
- Picking up the {{ data.vial }} gives a 10-second duration buff with a timer indicator above the player's head.
  - It also provides a new extra action ability.
  - Using the extra action button applies a 60-second debuff preventing that player from picking up the {{ data.vial }} vial.
- Pressing the extra action button within 10 seconds of picking up the {{ data.vial }} converts the nearby cauldron from green to purple.
  - This effect has no discernible duration and can therefore be applied to cauldrons prior to engaging the boss.
  - Converting a cauldron from green to purple will "drop" the {{ data.vial }} vial on the front of the affected cauldron.
- During the fight the boss will spawn a bomb slime from a cauldron on the nearby platform he recently jumped to.
- If the targeted cauldron is purple the spawned bomb is a {{ data.volatile_bomb }} instead.

## Strategy

### Before Engagement

1. Split up the group with (1) person nearby each of the (4) platforms, along with the remaining player also at the front-right platform. These people will be the {{ data.vial }} vial runners.
2. Ensure nobody gets in range of {{ data.boss }}.
3. Player #1 standing on the front-right platform clicks {{ data.vial }} and immediately presses their extra action button to throw it in the cauldron.
4. The {{ data.vial }} vial will immediately respawn.
5. Player #2 standing at front-right immediately picks up {{ data.vial }} and runs it to the next platform, spamming their extra action button. This process must be completed within 10 seconds without agroing the boss.
6. Person #3 waiting at the next platform clicks the {{ data.vial }} vial, runs to the next platform, and the process repeats.
7. Once all (4) cauldrons are turned purple you may engage the boss.

### During Fight

1. Fight {{ data.boss }} like normal.
2. During his two jump phases he'll spawn {{ data.volatile_bomb }} from the purple cauldron.
3. Kill the {{ data.volatile_bomb }}.
4. Repeat for the second jump phase.
5. Kill {{ data.boss }}.
