---
title: "Akki"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.myth-speaker-bestiary.Actor.ga1l2gjdrnb1ctRS" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/tengu
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Akki"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #216: The Acropolis Pyre"
name: "Akki"
level: "Creature 2"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[tengu]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Common, Tengu, Iblydan"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +8, Intimidation: +6, Performance: +8, Survival: +6, Sailing Lore: +7"
abilityMods: [4, 2, 3, 1, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder #216: The Acropolis Pyre_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +8, __Will__ +6"
hp: 38
health:
  - name: ""
  - name: HP
    desc: "38; __Resistances__ electricity 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Falchion|Falchion]], 3x [[Equipment/Javelin|Javelin]], [[Equipment/Scale Mail|Scale Mail]], [[Equipment/Grappling Hook|Grappling Hook]], [[Equipment/Rope|Rope]]"
abilities_mid:
  - name: ""
  - name: "Blood Storm"
    desc: "`pf2:r` (electricity) **Frequency** once per day\n\n**Trigger** Akki takes piercing or slashing damage\n* * *\n\n**Effect** Akki's blood sprays from the wound, forming a crimson cloud laced with tiny lightning bolts. Adjacent creatures take 1 electricity splash damage, and Akki is [[Conditions/Concealed|Concealed]] until the end of her next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Falchion"
    desc: "+10 (forceful, sweep)\n__Damage__  1d10 + 4 slashing plus *tempest-rage*"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+10 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing plus *tempest-rage*"

  - name: "**Melee** `pf2:1` Tournament Greatclub"
    desc: "+10 (backswing, nonlethal)\n__Damage__  1d10 + 4 bludgeoning plus *tempest-rage*"

  - name: "Tempest Rage"
    desc: "`pf2:1` (concentrate,electricity,emotion,mental) Akki channels the ferocity of a raging storm, causing her feathers and weapons to crackle with electricity. She gains 5 temporary Hit Points, deals an additional 1d4 electricity damage with her weapon Strikes, and cannot use actions (except [[Actions/Seek|Seek]]) with the concentrate trait unless they also have the rage trait. These effects last for 1 minute, until she falls [[Conditions/Unconscious|Unconscious]], or until the encounter ends, whichever comes first. After Akki uses this ability, she cannot do so again for 1d10 minutes."

  - name: "Thunderous Echo"
    desc: "`pf2:r` (sonic) **Trigger** Akki fails but does not critically fail a Strike against a target within 15 feet\n\n**Requirements** Akki is affected by Tempest Rage\n* * *\n\n**Effect** Even though her attack missed, a thunderclap follows an instant later in the weapon's wake. The Strike's target takes 1d4 sonic damage (`DC 16 Fortitude check` save). The target is [[Conditions/Deafened|Deafened]] for 1d4 rounds if they critically fail the saving throw."
 
```

```encounter-table
name: Akki
creatures:
  - 1: Akki
```




