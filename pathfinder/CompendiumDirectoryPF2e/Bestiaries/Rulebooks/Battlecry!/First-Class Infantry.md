---
title: "First-Class Infantry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.7IqiSn10q9ctmzys" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "First-Class Infantry"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "First-Class Infantry"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Warfare Lore: +24"
abilityMods: [8, 4, 5, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +23, __Will__ +20"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240; __Weaknesses__ area damage 12, splash damage 12"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "No Retreat"
    desc: "  These soldiers have been extensively trained to hold their ground no matter the situation. If any effect would force the first-class infantry to move, reduce the distance by 10 feet. Any time they would be affected by the [[Conditions/Fleeing|Fleeing]] condition, the first-class infantry is instead [[Conditions/Slowed|Slowed 2]] for the same duration."

  - name: "Troop Defenses"
    desc: "  **HP** 240 (4 segments); **Thresholds** 160 (3 segments), 80 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Bolt Salvo"
    desc: "`pf2:3`  The first-class infantry draws, loads, and shoots a salvo from their crossbows. The salvo is a 10-foot burst within 120 feet that deals 4d8 piercing damage (`DC 30 Reflex check` save). When the first-class infantry is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Clash of Steel"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The first-class infantry attacks each enemy in a 5-foot emanation, with a `DC 29 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 2d6+1 slashing damage\n\n`pf2:2` 4d6+10 slashing damage\n\n`pf2:3` 4d6+18 slashing damage"

  - name: "Drilled in Formations"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The first-class infantry uses [[Bestiary Ability Glossary/Change Formation|Change Formation]]. An first-class infantry unit typically knows the marching column and wedge formations."

  - name: "First-class Charge"
    desc: "`pf2:2`  The first-class infantry rushes forward with a hunger for battle. They Stride up to twice their Speed. At the end of their movement, each enemy within a 5-foot emanation takes 2d6+5 slashing damage, with a `DC 30 Reflex check` save."
 
```

```encounter-table
name: First-Class Infantry
creatures:
  - 1: First-Class Infantry
```



Soldiers who participate in multiple campaigns of war gain the experience necessary to become their military's finest fighting forces. First-class infantry troops are deployed on battlefields where winning the day is of the utmost importance.
