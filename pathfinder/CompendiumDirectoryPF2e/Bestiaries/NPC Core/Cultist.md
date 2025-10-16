---
title: "Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.GbPDSJeXjHc1VRN2" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Cultist"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "Cultist"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Deception: +3, Intimidation: +3, Occultism: +4, Society: +4, Stealth: +6, Cult Lore (for the cultist's own cult): +8"
abilityMods: [4, 3, 2, 1, -1, 0]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +8, __Will__ +4; (Will +2 vs. higher-ranking members of the cult)"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Leather Armor|Cultist Garb (Functions as Leather Armor)]], [[Equipment/Scholarly Journal|Occult Text]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+7 (agile, versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+6 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "Fanatical Frenzy"
    desc: "`pf2:1`  **Requirements** The cultist has taken damage and is neither [[Conditions/Fatigued|Fatigued]] nor already in a frenzy\n* * *\n\n**Effect** The cultist flies into a frenzy that lasts 1 minute. While frenzied, the cultist gains a +1 status bonus to attack rolls and a +2 status bonus to damage rolls, and they take a –2 penalty to AC. The cultist can't voluntarily stop their frenzy. After their frenzy, the cultist is fatigued."
 
```

```encounter-table
name: Cultist
creatures:
  - 1: Cultist
```



Hidden secrets and occult powers have an irresistible lure for many. Since the majority of these NPCs are spellcasters, consider using alternative spell lists to adjust their themes.
