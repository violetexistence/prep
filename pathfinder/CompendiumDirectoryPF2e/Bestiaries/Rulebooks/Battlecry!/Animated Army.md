---
title: "Animated Army"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.HIwXNbXV2sfSiYf4" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Animated Army"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Animated Army"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[mindless]]
trait_03: [[troop]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [6, 0, 6, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +14, __Will__ +13"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, (4 segments); Thresholds 120 (4 segments); Thresholds 80 (3 segments), 40 (2 segments); __Hardness__ 10; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 8, splash damage 8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor"
    desc: "  Like normal objects, the animated statues of the animated army have Hardness. This Hardness reduces any damage the animated army takes by an amount equal to the Hardness. Once an animated army is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 23."

  - name: "Troop Defenses"
    desc: "  **HP** 120 (4 segments); **Thresholds** 80 (3 segments), 40 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Battering Fists"
    desc: "`pf2:1` (magical) **Frequency** once per round\n* * *\n\n**Effect** The animated army makes a melee attack against each enemy in a 5-foot emanation (`DC 23 Reflex check` save). The damage dealt depends on the number of actions.\n\n`pf2:1` 1d8+2 bludgeoning damage\n\n`pf2:2` 2d8+8 bludgeoning damage\n\n`pf2:3` 3d8+10 bludgeoning damage"
 
```

```encounter-table
name: Animated Army
creatures:
  - 1: Animated Army
```



Animated statues usually appear in pairs or alone, hiding in plain sight among the other decor. Occasionally, a creator will fashion dozens of animated statues to serve as a nigh-unstoppable fighting force that doesn't complain or tire.
