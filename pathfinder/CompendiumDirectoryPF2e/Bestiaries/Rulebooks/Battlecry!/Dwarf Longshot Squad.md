---
title: "Dwarf Longshot Squad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.6miTTZwtCs2ouJbv" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Dwarf Longshot Squad"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Dwarf Longshot Squad"
level: "Creature 10"

alignment: ""
size: "grg"
trait_01: [[dwarf]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Dwarven"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Crafting: +22"
abilityMods: [1, 7, 5, 3, 1, 0]
speed: 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +22, __Will__ +16"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, (4 segments); Thresholds 120 (3 segments), 60 (2 segments); __Weaknesses__ area damage 12, splash damage 12"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 180 (4 segments); **Thresholds** 120 (3 segments), 60 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Bolts from the Blue"
    desc: "`pf2:2`  The dwarven longshots reload their crossbows, then launch a ranged attack in the form of a volley. This volley is a 15-foot burst within 120 feet that deals 6d6 piercing damage with a `DC 26 Reflex check` saving throw. When the dwarven longshot squad is reduced to 2 segments, this area decreases to a 10-foot burst."

  - name: "Brandish Bayonets!"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Using blades attached to their crossbows, the dwarven longshots engages in a coordinated melee attack against enemies in a 5-foot emanation, with a `DC 26 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 piercing damage\n\n`pf2:2` 2d8+11 piercing damage\n\n`pf2:3` 3d8+13 piercing damage"

  - name: "Hampering Fusillade"
    desc: "`pf2:2`  The dwarven longshots fire dozens of bolts in quick succession to slow down advancing enemies. Each creature in a 30-foot burst within 120 feet must attempt a `DC 26 Fortitude check` saving throw. On a failure, a creature takes a –10-foot circumstance penalty to its Speed for 1 minute. Spending an Interact action to remove the bolts ends this penalty.\n\n[[Bestiary Effects/Effect_ Hampering Fusillade|Effect: Hampering Fusillade]]"
 
```

```encounter-table
name: Dwarf Longshot Squad
creatures:
  - 1: Dwarf Longshot Squad
```



While many dwarves train to master hammers and shields, others seek to become masters of ranged weapons, usually sturdy and dwarven-built crossbows. Dwarven armies employ longshot squads as the first line of defense, especially outside of cramped tunnels and subterranean caverns.
