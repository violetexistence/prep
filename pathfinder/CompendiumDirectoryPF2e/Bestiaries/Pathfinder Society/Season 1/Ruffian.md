---
title: "Ruffian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pfs-season-1-bestiary.Actor.anjyGCh5n1fj2kn3" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Ruffian"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society: Season 1"
name: "Ruffian"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Common, Kelish"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Intimidation: +6, Stealth: +6"
abilityMods: [3, 2, 3, -1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Society: Season 1_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +8, __Will__ +6"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Club|Club]], [[Equipment/Sling|Sling]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 10x [[Equipment/Sling Bullets|Sling Bullets]]"
abilities_mid:
  - name: ""
  - name: "Attack of Opportunity"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+9 ()\n__Damage__  1d6 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Club"
    desc: "+8 (thrown 10 ft.)\n__Damage__  1d6 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+8 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d6 + 5 bludgeoning"

  - name: "Brutal Beating"
    desc: "  The ruffian's brutality shakes foes' confidence.\n\nWhen the ruffian deals damage on a critical hit, the target is [[Conditions/Frightened|Frightened 1]], and the ruffian can knock the target up to 10 feet away (this is forced movement)."

  - name: "Snagging Strike"
    desc: "`pf2:1`  **Trigger** The ruffian has one hand free, and their target is within reach of that hand.\n* * *\n\n**Effect** The ruffian makes a melee Strike while keeping one hand free. If this Strike hits, the target is [[Conditions/Off-Guard|Off-Guard]] until the start of the ruffian's next turn or until it leaves the ruffian's reach, whichever comes first."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The ruffian deals an extra 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Ruffian
creatures:
  - 1: Ruffian
```




