---
title: "Zecui Horde"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.ZV0sTglav4pah5iu" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Zecui Horde"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Zecui Horde"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +21, Stealth: +23"
abilityMods: [4, 7, 3, 1, 3, 1]
speed: 30 feet,  burrow 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 30
armorclass:
  - name: AC
    desc: "30 Thresholds 130 (3 segments), 65 (2 segments); __Fort__ +21, __Ref__ +24, __Will__ +18"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 195 (4 segments); **Thresholds** 130 (3 segments), 65 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Harden Chitin"
    desc: "`pf2:1`  The zecuis fuse their chitin into black metallic shells. The horde gains resistance 10 to all damage (except mental and spirit) until they next take a move action."

  - name: "Mandible Frenzy"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The horde makes a vicious bite attack against each enemy in a 5-foot emanation (`DC 27 Reflex check` save). The damage dealt depends on the number of actions.\n\n`pf2:1` 1d8+2 piercing damage\n\n`pf2:2` 2d8+12 piercing damage\n\n`pf2:3` 3d8+15 piercing damage"

  - name: "Mucus Deluge"
    desc: "`pf2:2`  The horde spits a volley of larva-infested mucus as a 10-foot burst within 30 feet. Each creature in the area must succeed at a `DC 27 Reflex check` save or be stuck to the nearest surface, [[Conditions/Immobilized|Immobilized]] until they [[Actions/Escape|Escape]] ([[Actions/escape dc=30|escape dc=30]]{DC 30}). Any creature so immobilized is exposed to zecui larvae at the end of each of its turns. When the zecui horde is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Subterranean Ambush"
    desc: "`pf2:1`  **Requirements** The zecui horde has burrowed into an ambush position just beneath a surface of dirt, sand, or a similar loose material\n* * *\n\n**Effect** The horde bursts from the ground and moves up to its Speed. The horde deals 1d8+2 piercing damage (`DC 29 Reflex check` save) to each enemy in a 5-foot emanation at the end of this movement."

  - name: "Zecui Larvae"
    desc: " (disease) **Saving Throw** `DC 30 Fortitude check`\n\n**Stage 1** visible lumps as the larvae move but no ill effect (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 3]] and controlled by the zecui larva (1 day)\n\n**Stage 5** the creature dies and an adult [[Monster Core/Zecui|Zecui]] can emerge from the corpse as an Interact action."
 
```

```encounter-table
name: Zecui Horde
creatures:
  - 1: Zecui Horde
```



A surprise raid by a swarm of the insectile zecui can easily wipe out an entire village overnight. When they don't devour their victims immediately, zecuis typically implant them with their own larvae and bury them in sprawling mass graves, where the developing zecui horde can lie dormant for years before suddenly erupting to the surface to wreak havoc on nearby settlements.
