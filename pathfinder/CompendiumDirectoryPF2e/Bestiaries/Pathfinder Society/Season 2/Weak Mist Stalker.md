---
title: "Weak Mist Stalker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pfs-season-2-bestiary.Actor.mREQ0kbYYSYsYb4e" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Weak Mist Stalker"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society Scenario #2-06: The Crashing Wave"
name: "Weak Mist Stalker"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Stealth: +10"
abilityMods: [4, 4, 2, 1, 5, 0]
speed: 20 feet,  climb 20 feet,  swim 30 feet
sourcebook: "_Pathfinder Society Scenario #2-06: The Crashing Wave_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +10, __Will__ +9"
hp: 43
health:
  - name: ""
  - name: HP
    desc: "43; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "Mist Vision"
    desc: "  The mist stalker ignores the [[Conditions/Concealed|Concealed]] condition from mist and fog."

abilities_mid:
  - name: ""
  - name: "Mist Cloud"
    desc: " (aura,primal,water) 15 feet. The mist stalker is surrounded by mist. Creatures in the aura are [[Conditions/Concealed|Concealed]]. If wind disperses the aura, it returns automatically at the start of the mist stalker's turn. This cloud is suppressed in water."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+12 (finesse, reach 10 feet, sweep, unarmed)\n__Damage__  2d8 + 2 bludgeoning plus *Grab*"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+2 bludgeoning damage, `DC 19 Fortitude check`\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Solidify Mist"
    desc: "`pf2:1` (primal,water) The mist stalker makes its mist cloud congeal, causing the aura to be difficult terrain until the start of the mist stalker's next turn.\n\nIn addition, the mist stalker can make the mist even thicker around a single Medium or smaller creature within the cloud. The creature must succeed at a `DC 18 Reflex check` save or become [[Conditions/Immobilized|Immobilized]] until it [[Actions/Escape|Escapes]] or it is no longer in the mist cloud's emanation."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Weak Mist Stalker
creatures:
  - 1: Weak Mist Stalker
```



The tentacled mist stalker shrouds itself in a cloak of mist through which its single, never-blinking eye can see with clarity, allowing it an advantage when stalking its prey.

* * *

Water elementals that become infused with cold or mist have increased mobility in regions outside of bodies of water.
