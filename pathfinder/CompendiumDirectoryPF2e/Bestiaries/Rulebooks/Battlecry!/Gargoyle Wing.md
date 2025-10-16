---
title: "Gargoyle Wing"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.6Nk6zk1seqFRQvl1" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/earth
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Gargoyle Wing"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Gargoyle Wing"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[earth]]
trait_03: [[troop]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Athletics: +18"
abilityMods: [4, 3, 4, -2, 3, -2]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +17, __Will__ +17"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (4 segments); Thresholds 100 (3 segments), 50 (2 segments; __Immunities__  bleed; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Death From Above"
    desc: "`pf2:r` (attack) **Trigger** The gargoyle wing is Flying, and a creature moves into an adjacent square below it\n* * *\n\n**Effect** The gargoyle wing swoops down with their talons. The triggering creature takes 2d8+9 slashing damage (`DC 28 Reflex check` save)."

  - name: "Troop Defenses"
    desc: "  **HP** 150 (4 segments); **Thresholds** 100 (3 segments), 50 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Catch and Release"
    desc: "`pf2:2`  The gargoyle wing attempts an Athletics checks to [[Actions/grapple|grapple]], comparing the result to the Fortitude DC of a number of Large or smaller creatures in a 5-foot emanation equal to the gargoyle wing's remaining number of segments, then Flies up to 40 feet, bringing any successfully [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] creatures along, and Releases them."

  - name: "Raking Swoop"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The gargoyle wing rips and tears with their stony talons at each enemy in a 5-foot emanation (`DC 28 Reflex check` save). The damage dealt depends on the number of actions.\n\n`pf2:1` 1d8+2 slashing damage\n\n`pf2:2` 2d8+9 slashing damage\n\n`pf2:3` 3d8+11 slashing damage"
 
```

```encounter-table
name: Gargoyle Wing
creatures:
  - 1: Gargoyle Wing
```



Normally solitary beasts that lurk in abandoned temples and other structures that afford them a place to hide among appropriately monstrous statuary, gargoyles occasionally band together to hunt challenging prey or simply to take communal pleasure in slaughtering the defenseless. Called wings, these groupings are usually short-lived, though that matters little to those who fall victim to their predations in the meantime.
