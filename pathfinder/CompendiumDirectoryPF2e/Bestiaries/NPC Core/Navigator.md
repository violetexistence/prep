---
title: "Navigator"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.nnrvoNBUzKyKQLu4" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Navigator"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "Navigator"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Nature: +11, Society: +8, Survival: +9, Sailing Lore: +14"
abilityMods: [0, 2, 1, 4, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +8, __Will__ +9"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], Scroll Case with Ship's Charts, [[Equipment/Writing Set|Writing Set]]"
  - name: "Chart a Course"
    desc: " (concentrate) By spending 10 minutes of work and succeeding at a Sailing Lore check, the navigator plots an optimal course.\n\nThe severity of environmental conditions other than temperature are reduced by one step for 24 hours (two steps on a critical success). This changes moderate damage to minor damage, winds that create greater difficult terrain cause only difficult terrain, and so on."

  - name: "Sailing Specialist"
    desc: "  For encounters involving navigation or sailing, the navigator is a 4th-level challenge."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+9 (agile, finesse, versatile s)\n__Damage__  1d4 + 4 piercing plus *navigators-edge*"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+9 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing plus *navigators-edge*"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+9 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "Navigator's Edge"
    desc: "  The navigator's Strikes deal an additional 1d6 damage when on a ship."
 
```

```encounter-table
name: Navigator
creatures:
  - 1: Navigator
```



A navigator uses celestial bodies and shipping lanes to determine routes.

* * *

Adventurers may need passage on a swift vessel, or they might face danger from raiders at sea or in coastal settlements.
