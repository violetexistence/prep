---
title: "Coralclaw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.myth-speaker-bestiary.Actor.QeY9MqsQ5EDAd0Zd" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Coralclaw"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #216: The Acropolis Pyre"
name: "Coralclaw"
level: "Creature 2"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8, Stealth: +7"
abilityMods: [4, 3, 2, -4, 1, -1]
speed: 20 feet,  swim 15 feet
sourcebook: "_Pathfinder #216: The Acropolis Pyre_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +11, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Coral Camouflage"
    desc: "  In reefs and rocky marine environments, a coralclaw can [[Actions/Hide|Hide]] and [[Actions/Sneak|Sneak]] without cover or being [[Conditions/Concealed|Concealed]]."

  - name: "Shuffler"
    desc: "  A coralclaw struggles to pivot quickly, leaving its hind limbs and tail vulnerable. When the coralclaw is [[Conditions/Off-Guard|Off-Guard]], it gains weakness 2 to physical damage except against effects for which the coralclaw has standard cover or greater cover."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Crusher Claw"
    desc: "+11 ()\n__Damage__  1d8 + 4 bludgeoning plus *Grab*"

  - name: "**Melee** `pf2:1` Piercer Claw"
    desc: "+11 (agile)\n__Damage__  1d6 + 4 piercing 1 bleed"

  - name: "Ambushing Snap"
    desc: "`pf2:1`  **Requirements** The coralclaw is hiding in corals and a creature that hasn't detected it is within 25 feet\n* * *\n\n**Effect** The coralclaw moves up to its swim Speed + 10 feet toward the triggering creature. When the creature is within reach, the coralclaw makes a melee Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] to this Strike."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d10 bludgeoning, `DC 18 Fortitude check`\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crushing Drag"
    desc: "`pf2:2` (attack,move) **Requirements** The coralclaw is grabbing or restraining a creature\n* * *\n\n**Effect** The coralclaw Constricts the creature, extends the [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] condition until the end of the coralclaw's next turn, and attempts an Athletics check to [[Actions/Reposition|Reposition]] the creature."

  - name: "Dislodged Armor"
    desc: "  Once the coralclaw is reduced to half its Hit Points, its AC decreases by 2, it gains a +5 circumstance bonus to its Speeds, and it loses coral camouflage. A coralclaw can repair its coral armor with 4 hours of work."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Coralclaw
creatures:
  - 1: Coralclaw
```




