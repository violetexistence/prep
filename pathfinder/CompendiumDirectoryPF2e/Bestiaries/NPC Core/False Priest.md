---
title: "False Priest"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.OAxxUyACpMlX3q1X" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "False Priest"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "False Priest"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Deception: +12, Performance: +12, Religion: +8, Society: +6"
abilityMods: [0, 4, 3, 0, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +12, __Will__ +10"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Rapier|Rapier]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Alchemist's Toolkit|Alchemist's Tools (Used as \"Blessed Items\" to Fool Marks)]], [[Equipment/Clothing (Ordinary)|Cloak]], [[Equipment/Religious Symbol (Wooden)|Religious Symbol (Wooden)]], 20x [[Equipment/Bolts|Bolts]], Collection of Fake Relics, [[Equipment/Backpack|Backpack]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+12 (deadly d8, disarm, finesse)\n__Damage__  1d6 + 8 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+12 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 8 bludgeoning"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+12 (range increment 60 feet, reload 1)\n__Damage__  1d6 + 4 piercing"

  - name: "Deceiver's Surprise"
    desc: "  On the first round of combat, if the false priest rolls Deception or Performance for initiative, creatures that haven't acted yet are [[Conditions/Off-Guard|Off-Guard]] to the false priest."

  - name: "Fickle Prophecy"
    desc: "`pf2:1` (emotion,mental) The false priest convinces someone of their omnipotence by attempting a `Deception check` check compared to the creature's Will DC.\n\nIf successful, the target gains 1d8+4 temporary Hit Points that last for 1 hour or until the false priest removes them by rebuking the target, whichever occurs first.\n\n[[Bestiary Effects/Effect_ Fickle Prophecy|Effect: Fickle Prophecy]]"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The false priest deals an extra 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures. This increases to 2d6 precision damage against creatures off-guard due to the false priest's [[Actions/Feint|Feint]] or deceiver's surprise."

  - name: "The Jig Is Up"
    desc: "`pf2:r`  **Frequency** once per hour\n\n**Trigger** The false priest critically fails a Deception or Performance check\n* * *\n\n**Effect** The false priest Strides."
 
```

```encounter-table
name: False Priest
creatures:
  - 1: False Priest
```



Belief is perhaps the strongest force in the universe. Instilling belief only to use it against someone in deceit, however, is the purview of a false priest.

* * *

Hidden secrets and occult powers have an irresistible lure for many. Since the majority of these NPCs are spellcasters, consider using alternative spell lists to adjust their themes.
