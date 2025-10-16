---
title: "Archer Regiment"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.pC4qg7AarAty1K7K" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Archer Regiment"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Archer Regiment"
level: "Creature 12"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Stealth: +22, Survival: +22"
abilityMods: [4, 7, 3, 1, 5, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +19, __Ref__ +25, __Will__ +22"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, (4 segments); Thresholds 140 (3 segments), 70 (2 segments); __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 210;**Thresholds** 140 (3 segments), 70 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Dagger Defense"
    desc: "`pf2:1`  The archer regiment draws daggers to attack close-range enemies. Each enemy in a 5-foot emanation must attempt a `DC 29 Reflex check` save. The damage depends on the number of actions. The archer regiment gains a +1 circumstance bonus to AC until the beginning of their next turn.\n\n`pf2:1` 2d4+2 piercing damage\n\n`pf2:2` 4d4+12 piercing damage\n\n`pf2:3` 4d4+15 piercing damage"

  - name: "Drilled in Formations"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The archer regiment uses [[Bestiary Ability Glossary/Change Formation|Change Formation]]. An archer regiment unit typically knows the loose and marching column formations."

  - name: "Rain of Arrows"
    desc: "`pf2:2`  The archer regiment fires their longbows in a coordinated volley. This volley is either a 15-foot burst within 200 feet that deals 4d8 piercing damage or a 10-foot burst within 100 feet that deals 6d8 piercing damage. Either effect has a `DC 29 Reflex check` save. When the archer regiment is reduced to 2 segments, both areas are reduced by 5 feet."
 
```

```encounter-table
name: Archer Regiment
creatures:
  - 1: Archer Regiment
```



Archer regiments are capable of filling the sky with arrows at great distances, making them vital to any war leader who wishes to weaken the enemy before they get close to allied units or encampments.
