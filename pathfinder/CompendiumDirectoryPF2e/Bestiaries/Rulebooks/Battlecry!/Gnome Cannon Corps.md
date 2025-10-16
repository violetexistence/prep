---
title: "Gnome Cannon Corps"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.C3WZzBOvaQ5LrlZ9" 
tags:
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Gnome Cannon Corps"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Gnome Cannon Corps"
level: "Creature 7"

alignment: ""
size: "grg"
trait_01: [[gnome]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: "Common, Fey, Gnomish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Arcana: +17, Crafting: +15"
abilityMods: [0, 4, 2, 6, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +15, __Will__ +18"
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

  - name: "Arcane Explosion"
    desc: "`pf2:3` (arcane,force) Aiming the gnome cannons toward the enemy, loading them, and firing them requires the troop's full attention. The cannons fire a 15-foot burst of bright magic within 200 feet that deals 2d12+2 force damage (`DC 22 Reflex check` save). A creature that fails their save is also [[Conditions/Dazzled|Dazzled]] for 1 round; this is a light and visual effect. The area of the explosion seems to twist and ripple for 1 minute afterward. A creature that attempts to move through the space must succeed at a `DC 22 Will check` save or treat the area as difficult terrain; this is an illusion and visual effect."

  - name: "Cannon Vent"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The gnome engineers vent the cannons' energy in a blast that hits all creatures in a 5-foot emanation (`DC 22 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6+2 fire damage\n\n`pf2:2` 2d6+8 fire damage\n\n`pf2:3` 3d6+10 fire damage"

  - name: "Direct Hit"
    desc: "`pf2:2`  The gnomes fire a more mundane round from one of their cannons at a single target within 60 feet, who takes 3d10+6 bludgeoning damage (`DC 22 Reflex check` save). On a failed save, the creature is also pushed 5 feet away from the troop."
 
```

```encounter-table
name: Gnome Cannon Corps
creatures:
  - 1: Gnome Cannon Corps
```



Inventive gnomes blend engineering and fey magic to create wondrous cannons, whose colorful blasts dazzle foes while creating areas of warped terrain. Only the cleverest generals understand how to use cannon corps to great advantage in unconventional warfare.
