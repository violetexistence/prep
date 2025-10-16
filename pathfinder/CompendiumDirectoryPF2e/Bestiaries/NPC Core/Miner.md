---
title: "Miner"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.GKDMvepxkEsUnN5d" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Miner"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "Miner"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +3, Athletics: +6, Survival: +4, Mining Lore: +4"
abilityMods: [2, 1, 3, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +7, __Ref__ +5, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Pick|Pick]], [[Equipment/Leather Armor|Miner's Harness (Functions as Leather Armor)]], [[Equipment/Hammer|Hammer]], [[Equipment/Lantern (Hooded)|Lantern (Hooded)]], 5x [[Equipment/Piton|Piton]], 2x [[Equipment/Rope|Rope]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pick"
    desc: "+6 (fatal d10)\n__Damage__  1d6 + 2 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+6 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 2 bludgeoning"

  - name: "Piton Pin"
    desc: "`pf2:1` (attack) **Requirements** The miner has their hammer in hand\n* * *\n\n**Effect** The miner Interacts to draw a piton, then hammers it into a creature to pin them in place, attempting an `DC 10 Athletics check` check made as an Interact action."
 
```

```encounter-table
name: Miner
creatures:
  - 1: Miner
```



Miners explore deep underground in search of minerals and rare ores, taking numerous precautions to keep themselves safe.

* * *

Society is built upon the backs of laborers.
