---
data:
  boss: '[Devos](https://www.wowhead.com/npc=167410/devos)'
  explosion: '[Abyssal Detonation](https://www.wowhead.com/spell=334625/abyssal-detonation)'
  spear: '[Spear of Duty](https://www.wowhead.com/spell=334649/spear-of-duty)'
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
requirement: Defeat Devos, Paragon of Doubt after hitting her with five Spears of Duty in the Spires of Ascension on Mythic difficulty.
title: '[ExSPEARiential](https://www.wowhead.com/achievement=14323/exspeariential)'
type: Group
zone: '[Spires of Ascension](https://www.wowhead.com/zone=12837)'
---

# {{ title }}

_{{ requirement }}_

> - Boss: {{ data.boss }}
> - Difficulty: **<span style="{{ difficulty.very_hard.style }}">{{ difficulty.very_hard.name }}</span>**
> - Type: **{{ type }}**
> - Zone: {{ zone }}

## Details

- During the {{ data.boss }} encounter (5) pairs of angels are fighting above the platform.
- When a pair of angels dies a floating {{ data.spear }} remains in the air.
- Interacting with a floating {{ data.spear }} keeps the player stationary and provides an extra action button to throw the spear, similar to the Phase 2 central spear during the normal encounter.
- Dropping off the front of the platform during the fight launches the player high into the air and provides a slow-fall wings buff.
- If a player drops off during Phase 2 the encounter winds effect will push the player more in that respective direction.

> The goal is to have **one** assigned player drop off the platform, float toward a {{ data.spear }}, and throw the spear at {{ data.boss }}. This process should be completed (5) times which will give {{ data.boss }} five debuff stacks.

## Planning

It is recommended that only one player handle {{ data.spear }} throwing throughout the encounter. This is because it can be difficult to receive credit for multiple spear hits on {{ data.boss }} at the same time. To ensure spear hits are counted you can optionally have one player import the following WeakAura, which sends a `/party` message when a {{ data.spear }} hit deals damage to {{ data.boss }}:

```
!WA:2!1rvZoUrrq41ApG0iuuIpef(rOjgbbeilibwjaHeE21ozr(VmEwCIyLMT901mtdZ0DRU7X76LBwCiNTeVa(mN8taAFcgzXtqoWdqEcO6z8grIiZLP6URVU((QQ6QrVM5nPnPp7JuIctgJdQrNe0)4HD9Jezc1pUp(j)mktlZilcGlmHXcvoXekdnSCiKUGtYzrHMufOtfz0fQfJIJ1G5r)17CR7Sh(THWJsfQXcg3m7WUdd66lDFZ3y9QgYBgvOnICRhNiPed4dZbU55KcCxIHfnLrnPEDWLksKHj46d81gIYmxLdAnjbwprceLBkZC3z13M83YerKm3CDI737skuKqGpVncZaT1IcvemKKdUTB726EA3A8Iy3JkmlCF0XbUi7CBzp(1WsYffCJZeGtpmLygutGpbJZN72ACh)GN26txsfHym40ZUAhbdnlKGF1XRWdR54z(voj9oMBavmjcoTdLIY70Pa5x7GXvF6yX5GQYCaqzKtNyrOpTJsjopuFUqOtBlsswJx6UqLolMXz6uhp8NXzPrXssaL(gFSAN5)4zzZQir(mIjtKOk4vzCFBzHUMcZkIJdqxupQB)X9oP)sksaBIV5xu6S(WkCU9fj(ylbODEUUyw1fmbXXUqfEuNbDEy3TfAiulHSmBM(SLvMht1olPG2y3Z)iyUq)s4Jvac3FY4U97FLf81(DMxbkLz2(iqT6Lx52xPQTcll16ZrElBFYCiOE9abf(Z9KV3)BRyTr5DFbZwe4KSFcZvOu)5LNlu0PkIC50DgEXcUrEZEk2LUpUGqXCcXniynYFFiX2x64Lji04nwYFPGdOApBMHKHI72(5fzgMJNMDjC7YFanKqK1WpkJO1wl1omEjF1x(nlTrBc683TvNsOIZFs9ZT9xRQcMTa5zqTSosWPSQ3foYp8n)EtQGiMvA7VIWz5vf0dkVrVRaIgMyuapXK(wLFGhhzX2Rl5vDUknydIEP1vBGlh6Lty8ELdqaLdlhvoU8X4)3913zh3FAn3F)9u)c26ZIx41VBVG1gr08609DAe(hTyuzRjsgoGXwu7OJaU9SV9vFEU5)iXv2NQydth)nXkSLaLbwu2)f1tI6z3Ys3zto0VB3H3VGr381IJEOCQ5YJMEWmuuXSeh1fxpjBX92ANKTfN9G4hjRZQBQfXHvdkB0OX(RX(uGwnx63F7nmEDIg91zLgYIRNa6nkiy0GMA)h0((TFqZ5)9t(3d
```

!> Be weary of {{ data.explosion }} if attempting this during ground phases. This ability does ~55,000 Arcane damage to anyone outside the safety bubble. If throwing during the ground phase the {{ data.spear }} thrower should be a tank or a player able to mitigate/immune the explosion while flying.

## Strategy

!> Regardless of strategy it is **highly** recommended to use (2) healers, as DPS checks are nonexistent.

### Ground Phase Strategy

> This strategy is generally easier to deal with, as the group can keep the boss in this phase indefinitely. Assuming the assigned {{ data.spear }} player can survive {{ data.explosion }} hits, this strategy is recommended.

1. Tank engages {{ data.boss }} as normal.
2. DPS should avoid attacking {{ data.boss }} lest she be pushed into her air phase too early.
3. The assigned {{ data.spear }} player should drop off the platform almost immediately to throw the first spear.
4. Repeat a few more times until all (5) {{ data.spear }} are thrown, or until no more angel pairs are dying.
5. Push {{ data.boss }} into the first air phase.
6. Throw the normal ground {{ data.spear }} after collecting orbs.
7. Back in ground phase, repeat step 3 until all (5) {{ data.spear }} have hit {{ data.boss }}.

!> If all (5) {{ data.spear }} are utilized but {{ data.boss }} _does not_ have (5) debuff stacks the attempt has failed. Wipe and try again.

8. Kill {{ data.boss }} as normal.

### Air Phase Strategy

> This strategy is best suited for groups where the {{ data.spear }} player cannot survive {{ data.explosion }}.

1. Tank engages {{ data.boss }} as normal.
2. DPS {{ data.boss }} until she reaches ~75%, then wait for 2-3 {{ data.spear }} to be spawned above.

> You can determine that a {{data.spear}} has spawned when you see a pair of angel corpses fall to the ground.

3. Push {{ data.boss }} to the air phase.
4. The {{ data.spear }} thrower should drop off the platform and start throwing spears as quickly as possible.
5. Once all active {{ data.spear }} are thrown the primary ground spear can be thrown to transition back to ground phase.
6. Push the boss back into the second air phase once the final 2-3 {{ data.spear }} have spawned.
7. Throw the last {{ data.spear }}.
8. Kill {{ data.boss }} as normal.

!> Take care with the DoT damage using this strategy, as the damage does ramp up the longer the air phase lasts.

### Combination Strategy

If the group is having trouble with either strict phase-based strategy then a combination strategy is a solid solution.

Simply allow the assigned {{ data.spear }} thrower to more fluidly react to timings of the fight, without worrying so much about DPS on {{ data.boss }}. For example, the initial {{ data.spear }} can be thrown almost immediately, prior to the first {{ data.explosion }}. Then 1-2 spears can be thrown during the first air phase, another during the second ground phase, and the final 1-2 during the last air phase.
