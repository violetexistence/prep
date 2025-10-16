---
title: "Hold Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.triumph-of-the-tusk-bestiary.Actor.u2xrjniEMLW7pWCw" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Hold Warrior"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Hold Warrior"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Intimidation: +7, Survival: +6"
abilityMods: [4, 2, 3, 0, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +10, __Ref__ +9, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Orc Necksplitter|Orc Necksplitter]], 6x [[Equipment/Javelin|Javelin]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The hold warrior is reduced to 0 HP\n* * *\n\n**Effect** The hold warrior avoids being knocked out and remains at 1 HP, but their [[Conditions/Wounded|Wounded]] value increases by 1. When they are [[Conditions/Wounded|Wounded 3]], they can no longer use this ability."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Necksplitter"
    desc: "+11 (forceful, sweep)\n__Damage__  1d8 + 6 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+9 (thrown 30 ft.)\n__Damage__  1d6 + 6 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 6 bludgeoning"
 
```

```encounter-table
name: Hold Warrior
creatures:
  - 1: Hold Warrior
```




