---
title: "Ratfolk Shank Squad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.2TE622Pc0ExYZ5dS" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/ratfolk
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Ratfolk Shank Squad"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Ratfolk Shank Squad"
level: "Creature 7"

alignment: ""
size: "grg"
trait_01: [[humanoid]]
trait_02: [[ratfolk]]
trait_03: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Deception: +15, Stealth: +17, Thievery: +17"
abilityMods: [0, 6, 2, 4, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +15, __Ref__ +18, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, (4 segments); Thresholds 80 (3 segments), 40 (2 segments); __Weaknesses__ area damage 8, splash damage 8"
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

  - name: "Dirty Tricks"
    desc: "`pf2:2`  The ratfolk feint and trip up their foes in a 5-foot emanation, attempting a single `Thievery check` check and comparing the result to each target's Reflex DC. On a success, the target is [[Conditions/Clumsy|Clumsy 1]] ([[Conditions/Clumsy|Clumsy 2]] on a critical success) until they take an Interact action to remove the condition."

  - name: "Poisoned Bolts"
    desc: "`pf2:2`  The shank squad draws hand crossbows to fire poisoned bolts in a volley. This volley is a 10-foot burst within 60 feet that deals 2d6 piercing damage and 2d6 poison damage with a `DC 22 Reflex check` save. When the shank squad is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Shank 'Em"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The shank squad makes a coordinated attack with shivs and daggers against each enemy in a 5-foot emanation, with a `DC 22 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d6 slashing damage and 1d4 precision damage\n\n`pf2:2` 2d6+3 slashing damage and 2d4 precision damage\n\n`pf2:3` 2d6+6 slashing damage and 3d4 precision damage"
 
```

```encounter-table
name: Ratfolk Shank Squad
creatures:
  - 1: Ratfolk Shank Squad
```




