---
title: "Monk Cadre"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.bBCYy91DecP2Y8Ax" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Monk Cadre"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Monk Cadre"
level: "Creature 14"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +28, Stealth: +25"
abilityMods: [8, 5, 2, 2, 4, 1]
speed: 35 feet,  climb 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +28, __Ref__ +26, __Will__ +25"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, (4 segments); Thresholds 180 (3 segments), 90 (2 segments); __Weaknesses__ area damage 15, splash damage 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 270 (4 segments); **Thresholds** 180 (3 segments), 90 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Coordinated Maneuvers"
    desc: "`pf2:2`  The monk cadre is practiced at putting their foes off-balance. The monks choose [[Actions/disarm|disarm]], [[Actions/grapple|grapple]], [[Actions/reposition|reposition]], or [[Actions/reposition|reposition]] and attempt an Athletics check to perform that action, comparing the result to the appropriate DC (Fortitude for Grapple and Reposition, Reflex for Disarm and Trip) of each enemy within a 5-foot emanation. This can result in a different degree of success for each target."

  - name: "Pummeling Punches"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The monks perform well-timed coordinated melee attacks against all enemies in a 5-foot emanation, with a `DC 31 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 2d8 bludgeoning damage\n\n`pf2:2` 4d8+8 bludgeoning damage\n\n`pf2:3` 4d8+16 bludgeoning damage"

  - name: "Qi Blast"
    desc: "`pf2:2` (force,occult) The monks channel their qi into an explosion of energy that affects all creatures in a 10-foot burst within 60 feet. This explosion deals 6d6 force damage with a `DC 31 Reflex check` save. When the monk cadre is reduced to 2 segments, this area decreases to a 5-foot burst."
 
```

```encounter-table
name: Monk Cadre
creatures:
  - 1: Monk Cadre
```



Many martial artists train to defend themselves and their allies against unwanted aggression, but sometimes the circumstances dictate that even the most peaceful monks must go to war. A cadre of studied monks is capable of dishing out great damage with punches and kicks, as well as focusing their qi into ranged blasts.
