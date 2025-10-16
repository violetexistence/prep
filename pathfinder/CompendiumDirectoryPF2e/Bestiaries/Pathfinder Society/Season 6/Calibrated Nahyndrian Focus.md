---
title: Calibrated Nahyndrian Focus
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Society Scenario #6-17: The Devil in the Details
aliases: "Compendium.pf2e.pfs-season-6-bestiary.Actor.6JGoaXdGGqq5j0pE" 
level: 10
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society Scenario #6-17: The Devil in the Details"
name: "Calibrated Nahyndrian Focus"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 32
sourcebook: "_Pathfinder Society Scenario #6-17: The Devil in the Details_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +33, "
hp: 100
health:
  - name: ""
  - name: "HP"
    desc: "100; __Hardness__ 18; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A metal lattice forged from warshards feeds into a dark purplish crystal that pulses with energy. If the configuration of the lattice changes, so does the energy the device emits."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three [[Actions/disable-device dc=27|disable-device dc=27]] (see Disabling the Focus under Event 1 on page 18)."
attacks:
  - name: ""

  - name: "Offensive Configuration"
    desc: "`pf2:r` **Trigger** Yollen activates the Nahyndrian Focus\n* * *\n\n**Effect** The Nahyndrian Focus shifts into attack mode and rolls initiative. All creatures without the unholy trait in within 60 feet must make a `DC 35 Fortitude check` save against 4d12+26 spirit damage."

  - name: "Select Condition"
    desc: "action The Nahyndrian Focus rolls a 1d4 to randomly decide whether it is going cause the [[Conditions/Clumsy|Clumsy]], [[Conditions/Drained|Drained]], [[Conditions/Enfeebled|Enfeebled]], or [[Conditions/Stupefied|Stupefied]] condition when it uses Inflict until the end of its turn. After the first round, it changes the random roll die to 1d6 as it does not pick the same condition it had in the previous round."

  - name: "Inflict"
    desc: "action (divine, magical, unholy) An unhealthy beam shoots out from the focus. One creature without the unholy trait within 60 feet of the Focus must make a `DC 31 Fortitude check` save.\n* * *\n\n**Critical Success** The target becomes immune to Inflict for 1 minute.\n\n**Success** The targe gains the condition from Select Condition with a value of 1 for 1 minute. If the creature is sickened from the Focus' reaction, the sickened condition increase by 1, up to a maximum of 3.\n\n**Failure** As success, but with a value of 2.\n\n**Critical Failure** As success, but with a value of 3."

  - name: "Routine"
    desc: "(3 actions) The Nahyndrian Focus uses Select Condition to determine which condition it is going to inflict. It then uses Inflict twice, usually on two different targets. If the focus is broken, it is [[Conditions/Slowed|Slowed 1]], and can only Inflict once per turn."

```

```encounter-table
name: Calibrated Nahyndrian Focus
creatures:
  - 1: Calibrated Nahyndrian Focus
```

