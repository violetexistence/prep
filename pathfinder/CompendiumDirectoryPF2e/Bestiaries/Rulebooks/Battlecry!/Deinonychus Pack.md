---
title: "Deinonychus Pack"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.NnnOp57rszKD3lBn" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Deinonychus Pack"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Deinonychus Pack"
level: "Creature 7"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[dinosaur]]
trait_03: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Stealth: +15"
abilityMods: [4, 4, 6, -4, 2, 3]
speed: 30 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +18, __Ref__ +15, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, (4 segments); Thresholds 80 (3 segments), 40 (2 segments); __Weaknesses__ area damage 6, splash damage 6"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 120 (4 segments); **Thresholds** 80 (3 segments), 40 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Jaws and Claws"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The pack makes a melee attack against each enemy in a 5-foot emanation (`DC 22 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6 piercing + 1d4 persistent bleed damage\n\n`pf2:2` 2d6+4 piercing + 2d4 persistent bleed damage\n\n`pf2:3` 3d6+6 piercing + 2d4 persistent bleed damage"

  - name: "Predator's Advantage"
    desc: "  Bleeding creatures take a –2 circumstance penalty to Reflex saves against a deinonychus pack's Jaws and Claws.\n\n[[Bestiary Effects/Effect_ Predator's Advantage|Effect: Predator's Advantage]]"

  - name: "Surround Prey"
    desc: "`pf2:2`  **Requirements** The deinonychus pack has at least 3 segments\n* * *\n\n**Effect** The pack Strides, positioning its segments so that at least two of them are adjacent to the same creature, and lashes out with its talons. That creature must succeed at a `DC 22 Reflex check` save or take 2d4 persistent bleed damage."
 
```

```encounter-table
name: Deinonychus Pack
creatures:
  - 1: Deinonychus Pack
```



Deinonychuses are widely known and feared both for the razor-sharp claws with which they savagely disembowel their prey and for their unmatched mastery of pack tactics, which enables determined deinonychus packs to consistently bring down prey much larger than themselves. Some iruxi and xulgath communities train these dinosaurs to act as battlefield skirmishers, weakening their enemies with hit-and-run tactics before closing in for the kill.
