---
title: "Goblin Rabble"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.IWVQdIhXQTmfaQqB" 
tags:
  - pf2e/creature/type/goblin
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Goblin Rabble"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Goblin Rabble"
level: "Creature 4"

alignment: ""
size: "grg"
trait_01: [[goblin]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +10, Stealth: +12, Thievery: +12"
abilityMods: [1, 5, 2, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +14, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, (4 segments); Thresholds 40 (3 segments), 20 (2 segments); __Weaknesses__ area damage 4, splash damage 4"
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

  - name: "Dogpile"
    desc: "`pf2:1`  The goblin rabble engage in as coordinated an attack as they can with their dogslicers, attacking each enemy in a 5-foot emanation (`DC 18 Reflex check` save). The damage depends on the number of actions. A creature who critically fails their save is also knocked [[Conditions/Prone|Prone]].\n\n`pf2:1` 1d6 slashing damage\n\n`pf2:2` 2d6+4 slashing damage\n\n`pf2:3` 2d6+7 slashing damage"

  - name: "Hobble Pursuit"
    desc: "`pf2:2`  The goblin rabble hamstring and hobble as many enemies as possible. Each enemy in a 5-foot emanation must attempt a `DC 18 Reflex check` save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes a –5-foot circumstance penalty to their Speeds.\n\n**Failure** The creature takes a –10-foot circumstance penalty to their Speeds and is [[Conditions/Slowed|Slowed 1]].\n\n**Critical Failure** The creature takes a –15-foot circumstance penalty to their Speeds and is slowed 1.\n\n[[Bestiary Effects/Effect_ Hobble Pursuit|Effect: Hobble Pursuit]]"

  - name: "Rush and Steal"
    desc: "`pf2:2`  Quickly moving in with grasping hands, the goblin rabble take what they can. The goblin rabble Strides up to twice their Speed. During this movement, the goblins Interact to pick up an unattended object no larger than 2 Bulk or attempt to [[Actions/Steal|Steal]] an item from a creature they are adjacent to; the goblins can pick up or Steal as many objects as they have remaining segments in any combination."
 
```

```encounter-table
name: Goblin Rabble
creatures:
  - 1: Goblin Rabble
```



Goblins lack the organization and discipline of their hobgoblin cousins but often more than make up for it with guile. Some goblin tribes like to terrorize trade routes under the cover of dusk. Focused on stripping valuables and escaping rather than finishing a fight, these groups of goblins excel at speed and identifying things of value to strip from their bewildered prey, using hit-and-run tactics since they tend to be outmatched more often than not.
