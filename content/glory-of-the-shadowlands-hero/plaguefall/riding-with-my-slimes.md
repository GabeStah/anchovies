---
data:
  boss: 'ALL Bosses'
  concentrated_plague: '[Concentrated Plague](https://www.wowhead.com/spell=330069/concentrated-plague)'
  doctor: '[Doctor Ickus](https://www.wowhead.com/npc=164967/doctor-ickus)'
  domina: '[Domina Venomblade](https://www.wowhead.com/npc=164266/domina-venomblade)'
  globgrog: '[Globgrog](https://www.wowhead.com/npc=164255/globgrog)'
  margrave: '[Margrave Stradama](https://www.wowhead.com/npc=164267/margrave-stradama)'
  plaguefallen: '[Plaguefallen](https://www.wowhead.com/spell=330092/plaguefallen)'
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
requirement: Defeat all bosses while affected by Plaguefallen within a single visit in Plaguefall on Mythic difficulty.
title: '[Riding with my Slimes](https://www.wowhead.com/achievement=14292/riding-with-my-slimes)'
type: Personal
zone: '[Plaguefall](https://www.wowhead.com/zone=13228)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_hard.style }}">{{ difficulty.very_hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- The {{ title }} achievement must be obtained within a _single run_ of {{ zone }}.
- Standing within almost any slime pool around the dungeon applies `1` stack of {{ data.concentrated_plague }}.
- Reaching `10` stacks of {{ data.concentrated_plague }} removes ALL stacks of {{ data.concentrated_plague }} and applies a new 120 second {{ data.plaguefallen }} debuff, which reduces movement speed significantly and lowers haste.

!> Dying **is** OK and will not prevent the ability to obtain the achievement. However, being dead the instant a given boss dies **will not** give you credit for that boss.

> It is possible to complete this achievement for the entire party in one run. However, it requires a lot of healing, so make sure your healer is comfortable handling the output required for the entire group's {{ data.plaguefallen }} DoT on top of normal boss damage.

## {{ data.globgrog }}

If group DPS is high:

1. Prior to engagement stand in slime near boss and gain {{ data.plaguefallen }}.
2. Engage {{ data.globgrog }}, use cooldowns, and DPS him down within 120 seconds.
3. Stay relatively close to {{ data.globgrog }} to easily dodge [Slime Wave](https://www.wowhead.com/spell=324667/slime-wave).

!> {{ data.globgrog }} will heal 20% HP if a large slime reaches it and deal AoE damage if a small slime reaches it.

If group DPS is low:

1. Engage and attack {{ data.globgrog }} as normal.
2. Stop DPS when {{ data.globgrog }} reaches ~20%.
3. Stand in slime and gain {{ data.plaguefallen }}. Try to time this shortly after killing recent slime spawns.
4. If necessary, CC slimes to finish {{ data.globgrog }} after everyone has {{ data.plaguefallen }}.

## {{ data.doctor }}

!> Due to the extremely low movement speed of {{ data.plaguefallen }} afflicted players it is best to attack {{ data.doctor }} and get him to enter his second jump phase (~33%).

1. Stand in slime and gain {{ data.plaguefallen }} on the group.
2. Finish {{ data.doctor }} as normal.

## {{ data.domina }}

1. Stack up {{ data.plaguefallen }} prior to engagement.
2. Attack {{ data.domina }} as usual.
3. If you have a player with teleport or other slow-reduction movement abilities they can run near Assassin webs to reveal them. Special abilities that can auto-reveal them such as [Mirror Image](https://www.wowhead.com/spell=55342/mirror-image) are ideal here.
4. Kill {{ data.domina }}.

!> If group damage is particularly low you _may_ need to gain {{ data.plaguefallen }} _after_ getting {{ data.domina }} low. However, this is difficult and risky, given the frequency of spider adds during the encounter.

## {{ data.margrave }}

!> The slime pools inside the boss's room **DO NOT** apply {{ data.concentrated_plague }}. The _only_ way to gain {{ data.plaguefallen }} is to stand in the normal slime pool shortly before the final hallway. Therefore, relatively high DPS is required to complete this achievement, as {{ data.margrave }} must die within the 120-second duration of {{ data.plaguefallen }} since it cannot be gained after to engagement.

1. Have everyone simultaneously step into slime and gain {{ data.plaguefallen }} prior to engagement.
2. Plan for and use any movement boosting abilities available to the group to get into the boss room after gaining {{ data.plaguefallen }}.
3. Engage and fight {{ data.margrave }} as normal.
4. Pay particular attention to the location of tentacle slams due to hindered movement speed.
5. {{ data.margrave }} automatically phases away at 66% and 33%, so plan cooldowns accordingly, e.g. Use potions at 100%, use personal CDs at 66%, and use Bloodlust at 33%.
6. If the timer is going to expire prior to the kill you should intentionally wipe by standing in boss-room slime pools and try again. Dying does not reset the achievement progress.
