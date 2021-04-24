---
data:
  ball: '[Shadow Ball](https://www.wowhead.com/spell=330004/shadow-ball)'
  boss: '[General Kaal](https://www.wowhead.com/npc=165318/general-kaal)'
  container: '[Filled Anima Container](https://www.wowhead.com/npc=169594/filled-anima-container)'
  knockback: '[Gloom Squall](https://www.wowhead.com/spell=322895/gloom-squall)'
  radiance: '[Shining Radiance](https://www.wowhead.com/spell=324086/shining-radiance)'
  slammed: '[Slammed!](https://www.wowhead.com/spell=330055/slammed)'
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
requirement: Defeat General Kaal while affected by Slammed! in the Sanguine Depths on Mythic difficulty.
title: '[Kaal-ed Shot](https://www.wowhead.com/achievement=14289/kaal-ed-shot)'
type: Personal
zone: '[Sanguine Depths](https://www.wowhead.com/zone=12842)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_hard.style }}">{{ difficulty.very_hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- `5` {{ data.container }} sit on the right side of the {{ data.boss }} gauntlet hallway.
- Opening a container applies the {{ data.ball }} debuff which deals minor Shadow damage every `4` seconds.

!> Once you activate a {{ data.container }} you have **one chance** to get through the {{ data.boss }} gauntlet, complete the achievement, and defeat the boss. If you die or fail you must reset and reclear the entire zone to try again.

- On the left wall of the {{ data.boss }} boss platform hangs a {{ data.container }}.
- Being hit by {{ data.knockback }} from {{ data.boss }} during the fight knocks players back.
- Being knocked toward the {{ data.container }} provides a **very brief** moment to interact with the {{ data.container }} before falling to one's death.
- Right-clicking or otherwise interacting with the {{ data.container }} while afflicted by {{ data.ball }} transports the player back to the platform and gives the {{ data.slammed }} debuff required for the achievement.

!> The {{ data.container }} **cannot** be targeted, so it must be manually right-clicked or interacted with using more reliable means as discussed below.

## Planning

!> **DO NOT** run ahead toward the bridge leading to the {{ data.boss }} gauntlet until the entire group is prepared. If you do so, step back across the bridge and wait for the spawned dog pack to come forward and be killed.

> If the entire group is going to do the achievement simultaneously you may want to use `2` healers for the gauntlet as well as the actual {{ data.boss }} fight. Any individual that dies cannot receive credit, so take your time and ensure survival throughout the entire process.

- Fight through the {{ data.boss }} gauntlet as normal then clear the final pre-boss trash room.
- Ensure that your Focus unit frame is displayed on screen and is reasonably large in size.
- Create a `FocusMouseover` macro: `/focus [target=mouseover,nodead]`. Since the {{ data.container }} cannot be targeted this macro allows you to hover your cursor over the {{ data.container }} and press the macro, which will set the {{ data.container }} as your Focus unit.
- Open your targeting key bindings via `ESC > Key Bindings > Targeting` and set `Interact with Focus` to an easily spammable key (e.g. `mousewheel`).
  - Now, you can hover your cursor on top of your Focus frame (which has the {{ data.container }} assigned) then spam your set `Interact with Focus` binding. This will attempt to interact with the {{ data.container }} exactly as if you had right-clicked it.

!> It is **HIGHLY** recommended everyone in the group tests their configuration in the pre-boss room before engaging. Use a summoned interactive entity such as a [Jeeves](https://www.wowhead.com/item=49040/jeeves) or [Repair Bot](https://www.wowhead.com/item=18232/field-repair-bot-74a). Have everyone mouse over [Jeeves](https://www.wowhead.com/item=49040/jeeves) and use their `FocusMouseover` macro to set him as Focus, then start moving toward him while spamming the `Interact with Focus` button. As soon as you get in range the normal repair/sell screen should appear, indicating your configuration is working properly.

- Once everyone is ready, carefully sneak into the {{ data.boss }} room and from the doorway use `FocusMouseover` macros to set the {{ data.container }} as your Focus unit.
- Finally, the group leader should carefully hug the left edge and set a few ground raid markers.
  - One should be straight across from the {{ data.container }} on the edge. This `LaunchMarker` indicates where players should stand when getting knocked toward the {{ data.container }}.
  - The other should be ~10-15 yards to the side of the first marker. This `BubbleMarker` indicates where the tank or assigned shield holder should drop the {{ data.radiance }} safety bubble.

## Strategy

!> Prepare **everything** mentioned above prior to engaging {{ data.boss }}. For this strategy it is assumed the tank will be placing the {{ data.radiance }} bubble.

1. Engage and pull {{ data.boss }} to the `BubbleMarker` location.
2. When not dodging blades the entire group should be standing either at the `BubbleMarker` to avoid knockback or on the `LaunchMarker` ready to be launched:

If {{ data.boss }} reaches full energy and teleports to the _opposite side_ location to cast {{ data.knockback }} then players can stand on `LaunchMarker` with mouse cursor hovering over their focus frame set to {{ data.container }}, spamming their `Interact with Focus` hotkey.

Otherwise, if {{ data.boss }} reaches full energy and teleports to the _nearby_ or _entrance_ locations, it **IS NOT** safe to launch, so players should move to `BubbleMarker` to safely be in {{ data.radiance }}.

3. Repeat step 2 every 100 energy until all **non-tank** players have been launched and acquired the {{ data.slammed }} buff needed for the achievement. Now it is the tank's turn to be launched, assuming they are also doing the achievement.
4. If the tank is still dropping {{ data.radiance }} they must be quick to react to properly drop {{ data.radiance }} at the `BubbleMarker` position, move to `LaunchMarker`, and be spamming `Interact with Focus` hovering their {{ data.container }} focus frame. Failing to perform these steps properly will mean either the tank fails and dies or the group dies from not having {{ data.radiance }}.

!> It is possible to right-click the shield buff off and drop it for another player to pick up. If your group wants to assist the tank player once it is their turn to launch, having someone else handle the {{ data.radiance }} placement at `BubbleMarker` is simpler.

> During the brief period that the tank is off the platform {{ data.boss }} will agro and attack other players. Try to have a resilient offtank ready for that moment (i.e. bear form druid, paladin with a shield, etc).

5. Once everyone has launched just kill {{ data.boss }} as normal.

> Remember, anyone that fails cannot get the achievement this time around, but those that managed to get {{ data.slammed }} and survive the fight will get credit. Come back again for those that missed until you're all done!
