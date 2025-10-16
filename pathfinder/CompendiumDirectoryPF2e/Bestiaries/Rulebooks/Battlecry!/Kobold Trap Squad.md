---
title: "Kobold Trap Squad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.X5UZZ6b6sq5JVJN9" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Kobold Trap Squad"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Kobold Trap Squad"
level: "Creature 4"

alignment: ""
size: "grg"
trait_01: [[humanoid]]
trait_02: [[kobold]]
trait_03: [[troop]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: "Common, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Crafting: +10, Survival: +10"
abilityMods: [1, 4, 0, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, (4 segments); Thresholds 40 (3 segments), 20 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 60 (4 segments); **Thresholds** 40 (3 segments), 20 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Group Scamper"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The kobolds Stride up to their Speed plus 5 feet and gain a +2 circumstance bonus to AC against reactions triggered by this movement. If they end this movement with at least 1 segment adjacent to any enemy, the squad is [[Conditions/Off-Guard|Off-Guard]] until the beginning of its next turn."

  - name: "Hasty Traps"
    desc: "`pf2:2` (manipulate) The kobolds hastily prepare a handful of rudimentary traps in their vicinity until the beginning of their next turn. The next creature who moves adjacent to the trap squad triggers a trap and must attempt a `DC 18 Reflex check` save. On a failure, the creature takes 1d4 persistent bleed damage (2d4 persistent bleed damage on a critical failure). A creature taking persistent bleed damage from Hasty Traps takes a –5-foot enhancement penalty to its Speed. This occurs to as many creatures as the kobold trap squad has segments when it performed the action, but a single creature can trigger only one trap per turn.\n\n[[Bestiary Effects/Effect_ Hasty Traps|Effect: Hasty Traps]]"

  - name: "Sling Barrage"
    desc: "`pf2:2`  The kobolds draw their slings, then launch a ranged barrage of stones. This barrage is a 10-foot burst within 50 feet that deals 3d4 bludgeoning damage with a `DC 18 Reflex check` save. When the squad is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Spear Jabs"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The kobold trap squad engages in a coordinated melee attack against all enemies in a 5-foot emanation, with a `DC 18 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d6 piercing damage\n\n`pf2:2` 2d6+4 piercing damage\n\n`pf2:3` 2d6+7 piercing damage"
 
```

```encounter-table
name: Kobold Trap Squad
creatures:
  - 1: Kobold Trap Squad
```



Kobold trap squads generally protect their warrens, but these groups sometimes range outside of their lairs at the behest of a powerful patron. Their goals are usually to scout a given location, but they can be tasked with procuring an item or resource for the good of the warren.
