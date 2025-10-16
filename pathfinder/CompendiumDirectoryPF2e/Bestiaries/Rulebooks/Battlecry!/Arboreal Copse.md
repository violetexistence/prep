---
title: "Arboreal Copse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.yHSlSwhlmgTZYNWs" 
tags:
  - pf2e/creature/type/plant
  - pf2e/creature/type/troop
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Arboreal Copse"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Arboreal Copse"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[plant]]
trait_02: [[troop]]
trait_03: [[wood]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision"
languages: "Arboreal, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Stealth: +16"
abilityMods: [5, 1, 5, 2, 5, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +16, __Will__ +18"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (4 segments); 150 (4 segments); Thresholds 100 (3 segments), 50 (2 segments); __Weaknesses__ area damage 10, axe vulnerability 8, fire 12, splash damage 10; __Resistances__ bludgeoning 8, piercing 8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Reactive Attack"
    desc: "`pf2:r`  **Trigger** An enemy within 5 feet of the arboreal copse uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The arboreals swing their stone swords. The triggering enemy takes 2d8+9 bludgeoning damage (`DC 25 Reflex check` save). If the creature critically fails their saving throw and the trigger was a manipulate action, the troop disrupts that action."

  - name: "Troop Defenses"
    desc: "  **HP** 150 (4 segments); **Thresholds** 100 (3 segments), 50 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Raise Shields"
    desc: "`pf2:1`  The arboreal wardens of the copse raise their shields in tandem, gaining a +2 circumstance bonus to AC and Reflex saves."

  - name: "Shoving Shield Wall"
    desc: "`pf2:2`  The arboreal copse Strides. All enemies whose square the copse begins in or passes through during their movement take 5d6 bludgeoning damage (`DC 25 Fortitude check`). On a failed saving throw, the arboreal copse carries the creature along on their shields, moving them in the same distance and direction for the rest of their Stride."

  - name: "Sword Bash"
    desc: "`pf2:1`  The arboreal copse uses their blunt stone longswords to pummel its foes. Each enemy in a 10-foot emanation must attempt a `DC 25 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+1 bludgeoning damage\n\n`pf2:2` 2d8+9 bludgeoning damage\n\n`pf2:3` 3d8+10 bludgeoning damage"
 
```

```encounter-table
name: Arboreal Copse
creatures:
  - 1: Arboreal Copse
```



Though arboreal wardens typically remain within the boundaries of the forests they protect, they occasionally gather into copses to seek information about potential threats to report back to arboreal regents. Arboreals are typically slow to act, but copses must sometimes make quick judgment calls when faced with imminent dangers.
