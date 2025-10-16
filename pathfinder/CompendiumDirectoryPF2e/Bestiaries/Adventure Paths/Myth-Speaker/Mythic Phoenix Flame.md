---
title: "Mythic Phoenix Flame"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.myth-speaker-bestiary.Actor.2La4fXp6iq11vQpP" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2e/creature/type/mythic
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Mythic Phoenix Flame"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #216: The Acropolis Pyre"
name: "Mythic Phoenix Flame"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[elemental]]
trait_02: [[fire]]
trait_03: [[mythic]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Pyric"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +15"
abilityMods: [3, 4, 2, -1, 3, 0]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder #216: The Acropolis Pyre_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +12, __Will__ +11"
hp: 48
health:
  - name: ""
  - name: HP
    desc: "48; __Immunities__  bleed,  fire,  paralyzed,  poison,  sleep; __Weaknesses__ cold 5; __Resistances__ mythic 4"
abilities_top:
  - name: ""

  - name: "Smoke Vision"
    desc: "  The mythic phoenix flame ignores the [[Conditions/Concealed|Concealed]] condition from smoke."

  - name: "Titanic Might"
    desc: "  The phoenix flame ignores size limitations when performing actions like [[Actions/Grapple|Grapple]] or [[Actions/Trip|Trip]]."

abilities_mid:
  - name: ""
  - name: "Flame Cloak"
    desc: " (aura,fire,primal) 10 feet. 1d6 fire, `DC 18 Reflex check` save. A creature that critically fails its save takes 1d4 persistent fire damage."

  - name: "Mythic Ferocity"
    desc: "`pf2:r`  **Cost** 1 Mythic Point\n\n**Trigger** The phoenix flame is reduced to 0 HP\n* * *\n\n**Effect** The phoenix flame avoids being knocked out and regains 4d10 healing Hit Points, but its wounded value increases by 1. When it is [[Conditions/Wounded|Wounded 3]], it can no longer use this ability."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fiery Talon"
    desc: "+12 (fire, magical)\n__Damage__  1d10 + 5 slashing plus *Grab* 1d10 fire plus *Grab*"

  - name: "Breath of Smoke"
    desc: "`pf2:1`  **Requirements** The phoenix flame has a creature Grabbed\n* * *\n\n**Effect** The phoenix breathes into the lungs of the [[Conditions/Grabbed|Grabbed]] creature, which must attempt a `DC 18 Fortitude check` save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Breath of Smoke for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 2]]."

  - name: "Inferno Dance"
    desc: "`pf2:2`  The phoenix Strides up to its Speed, leaving a trail of blazing flame through each space it passes through that lasts until the end of the phoenix's next turn. This trail is difficult terrain and deals 5d6 fire damage to each creature in its path (`DC 18 Reflex check` save)."

  - name: "[[Creature Family Ability Glossary/(Mythic) Mythic Power|Mythic Power]]"
    desc: "  The creature has a pool of 3 Mythic Points, and can spend those Mythic Points for any of the actions it has."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mythic Phoenix Flame
creatures:
  - 1: Mythic Phoenix Flame
```




