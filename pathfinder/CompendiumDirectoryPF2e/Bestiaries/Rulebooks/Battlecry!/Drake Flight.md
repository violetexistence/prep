---
title: "Drake Flight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.2CfSF5X4YlLPNKgh" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Drake Flight"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Drake Flight"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[troop]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +30, Intimidation: +24, Survival: +24"
abilityMods: [8, 5, 4, -2, 2, 1]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +23, __Will__ +20"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, (4 segments), Thresholds 160 (3 segments), 80 (2 segments); __Immunities__  paralyzed,  sleep; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ acid 5, cold 5, fire 5, poison 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 240 (4 segments), **Thresholds** 160 (3 segments), 80 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Draconic Onslaught"
    desc: "`pf2:1`  The drakes frenzy, lashing out with fangs and tails. Each enemy in a 10-foot emanation attempts a `DC 30 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 2d8 untyped damage\n\n`pf2:2` 3d8+10 untyped damage\n\n`pf2:3` 4d8+14 untyped damage"

  - name: "Drake Breath"
    desc: "`pf2:2` (primal,acid) Certain drakes within the flight bring their breath weapon (or similar ability) to bear, exhaling energy that explodes in a 15-foot burst within 120 feet. This explosion deals 5d6 untyped damage (acid, cold, fire, or poison damage); the ability gains the corresponding trait. The drake flight can't choose the same damage type until it uses this ability with a different damage type. When the drakes are reduced to 2 segments, this area decreases to a 10-foot burst."

  - name: "Speed Surge"
    desc: "`pf2:1`  **Frequency** three times per day\n* * *\n\n**Effect** The drake flight Strides or Flies twice."
 
```

```encounter-table
name: Drake Flight
creatures:
  - 1: Drake Flight
```



Though drakes from different biomes rarely interact with one another due to geographical distance, a powerful creature, ancient artifact, or natural catastrophe could bring together multiple types of drakes into a single terrifying, living catastrophe. Such a flight can be a terror to behold on the battlefield.
