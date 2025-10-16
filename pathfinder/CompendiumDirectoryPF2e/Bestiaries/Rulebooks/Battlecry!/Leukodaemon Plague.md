---
title: "Leukodaemon Plague"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.jibQ9pSTYlWKkJ7z" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/troop
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Leukodaemon Plague"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Leukodaemon Plague"
level: "Creature 14"

alignment: ""
size: "grg"
trait_01: [[daemon]]
trait_02: [[fiend]]
trait_03: [[troop]]
trait_04: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Daemonic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Intimidation: +25, Medicine: +28, Religion: +28, Stealth: +25, Survival: +23"
abilityMods: [7, 5, 1, 3, 5, 3]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +22, __Ref__ +25, __Will__ +28"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255, (4 segments); Thresholds 170 (3 segments), 85 (2 segments); __Immunities__  death effects,  disease; __Weaknesses__ area damage 15, splash damage 15, holy 15"
abilities_top:
  - name: ""

  - name: "Plaguesense"
    desc: "  A leukodaemon plague senses any creature with a disease, and knows the type and current stage of all diseases carried by any creature within range."

abilities_mid:
  - name: ""
  - name: "Infectious Aura"
    desc: " (aura,disease) 30 feet. Leukodaemons radiate infection. All creatures within 30 feet of a leukodaemon plague take a –2 status penalty to saves against disease. If a creature within range contracts or progresses a disease, all adjacent creatures are exposed to the same disease, at the same DC."

  - name: "Troop Defenses"
    desc: "  **HP** 255 (4 segments); **Thresholds** 170 (3 segments), 85 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +0; __7th __  _[[Spells/Dispel Magic|Dispel Magic]]_; __5th __  _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Daemonic Pestilence"
    desc: " (disease) The leukodaemon plague can telepathically communicate with the afflicted creature at any distance on the same plane\n\n**Saving Throw** `DC 34 Fortitude check`\n\n**Stage 1** carrier (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 4** drained 2 (1 day)\n\n**Stage 5** [[Conditions/Drained|Drained 3]] (1 week)\n\n**Stage 6** dead"

  - name: "Infected Jaws and Claws"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The leukodaemons unleash an onslaught of blows against each enemy in a 10-foot emanation (`DC 31 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d10+3 untyped damage plus daemonic pestilence\n\n`pf2:2` 3d10+9 untyped damage plus daemonic pestilence\n\n`pf2:3` 4d10+12 untyped damage plus daemonic pestilence"

  - name: "Pestilent Wheeze"
    desc: "`pf2:2` (divine,unholy) The leukodaemons exhale a 30-foot cone of disease-ridden black flies that deal 5d8 piercing damage (`DC 31 Reflex check` save). A creature that fails the save also becomes [[Conditions/Sickened|Sickened 1]] (or [[Conditions/Sickened|Sickened 2]] on a critical failure). When the leukodaemon plague is reduced to 2 segments, this area decreases to a 20-foot cone."

  - name: "Quicken Pestilence"
    desc: "`pf2:1` (divine,manipulate) The leukodaemons coax a disease into full bloom. They choose a target within their infectious aura that's currently affected by a disease. That creature must attempt a Fortitude save against the disease as if the interval for the disease's current stage had passed."
 
```

```encounter-table
name: Leukodaemon Plague
creatures:
  - 1: Leukodaemon Plague
```



Daemons are shaped by, and devoted to, the destruction of life in all its forms. Leukodaemons serve the Apocalypse Rider of Pestilence, spreading disease across the Universe with their very touch. A small army of leukodaemons has the potential to wipe out a small country—or more—if left unchecked.
