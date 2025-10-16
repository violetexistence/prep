---
title: "Surgeon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.oaqt9bociCp9e3Yr" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Surgeon"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "Surgeon"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Crafting: +10, Diplomacy: +8, Medicine: +16"
abilityMods: [1, 3, 1, 2, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +7, __Will__ +10"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/War Razor|Scalpel]], [[Equipment/Temple Sword|Bonesaw (Functions as a Temple Sword)]], [[Equipment/Healer's Toolkit|Healer's Tools]]"
  - name: "Doctor's Hand"
    desc: "  When the surgeon rolls a critical failure on a check to [[Actions/Treat Disease|Treat Disease]], [[Actions/Treat Poison|Treat Poison]], or [[Actions/Treat Wounds|Treat Wounds]], they get a failure instead."

abilities_mid:
  - name: ""
  - name: "[[Actor.hHQNqQlKh6AEHmW9.Item.zNtJDSruQtC6hlYE|Medical Specialist]]"
    desc: "  In medical matters, a surgeon is a 6th-level challenge."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scalpel"
    desc: "+11 (agile, finesse, versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "**Ranged** `pf2:1` Scalpel"
    desc: "+11 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 1 bludgeoning"

  - name: "**Melee** `pf2:1` Bonesaw"
    desc: "+9 (trip)\n__Damage__  1d8 + 1 slashing"

  - name: "Medical Malpractice"
    desc: "`pf2:1`  The surgeon attempts a `Medicine check` check against the Fortitude DC of one living creature they can see within 60 feet.\n\nOn a success, the surgeon's melee Strikes deal an extra 1d6 precision damage against that creature (2d6 on a critical success) until 1 minute passes or the surgeon critically hits that creature, whichever comes first.\n\nUsing this action again ends any previous one. A surgeon can target an individual creature no more than once per day with this ability."
 
```

```encounter-table
name: Surgeon
creatures:
  - 1: Surgeon
```



The surgeon specializes in the physical alteration of the body to prevent the spread of disease, removing necrotic and decaying flesh to help the whole to survive. Few healers know the science of anatomy and physiology better.

* * *

The world is a dangerous place. Thankfully, there are those who devote their lives to easing the pain and suffering of others.
