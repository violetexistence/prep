---
title: "Boggard Scouting Party"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.5JQ5nf7LZt05EYiF" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Boggard Scouting Party"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Boggard Scouting Party"
level: "Creature 6"

alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[humanoid]]
trait_04: [[troop]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Boggard, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +15, Stealth: +13"
abilityMods: [5, 4, 2, 0, 2, 0]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +14, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, (4 segments); Thresholds 60 (3 segments), 30 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 90 (4 segments); **Thresholds** 60 (3 segments), 30 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Chorus of Croaks"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The boggard scouting party unleashes a chorus of terrifying croaks. Any non-boggard within 30 feet becomes [[Conditions/Frightened|Frightened 1]] unless they succeed at a `DC 21 Will check` save; those who critically succeed are temporarily immune for 1 minute."

  - name: "Coordinated Tongue Pull"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Several boggards use their tongues to grapple an enemy within 10 feet to pull them closer. The target must attempt a `DC 21 Reflex check` save. On a failure, they are [[Conditions/Grabbed|Grabbed]] and pulled 5 feet closer to the scouting party. A creature grabbed in this way isn't [[Conditions/Immobilized|Immobilized]], but it can't move more than 10 feet from the scouting party. A creature can sever one of the tongues with a Strike against AC 21 that deals at least 5 slashing damage. This doesn't damage the scouting party."

  - name: "Morningstar Massacre"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The boggards execute coordinated melee attacks against each enemy in a 5-foot emanation, with a `DC 21 Reflex check` save. The damage dealt depends on the number of actions.\n\n`pf2:1` 1d6 untyped damage\n\n`pf2:2` 2d6+7 untyped damage\n\n`pf2:3` 2d6+11 untyped damage"

  - name: "Sling Barrage"
    desc: "`pf2:2`  The dreadknot draws and loads slings to launch a coordinated barrage. This barrage is a 10-foot burst within 50 feet that deals 3d6 bludgeoning damage (`DC 21 Reflex check` save). When the scouting party is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Swamp Passage"
    desc: "  A boggard scouting party ignores difficult terrain caused by swamp terrain features."
 
```

```encounter-table
name: Boggard Scouting Party
creatures:
  - 1: Boggard Scouting Party
```



Boggard scouting parties run ahead of other boggard troops to get the lay of the land. They sometimes engage if they think they can quickly vanquish an enemy force.
