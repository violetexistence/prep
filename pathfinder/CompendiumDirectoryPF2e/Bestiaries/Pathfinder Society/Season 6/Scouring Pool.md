---
title: Scouring Pool
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Society Scenario #6-16: The Heart of the City
aliases: "Compendium.pf2e.pfs-season-6-bestiary.Actor.o43EV2QLt9eR6lv5" 
level: 7
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society Scenario #6-16: The Heart of the City"
name: "Scouring Pool"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 17
sourcebook: "_Pathfinder Society Scenario #6-16: The Heart of the City_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +12, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Hardness__ 17; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert) to notice the enticing effects of the pool"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The swirling water in this pool entices anyone who can see or hear it to wander into its depths, drowning its victims."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "`DC 27 Thievery check` to scratch out the runes creating the effect, `DC 23 Occultism check` (expert) or `DC 23 Demon Lore check` (expert) to determine the password that identifies the party as believers, or [[Spells/Dispel Magic|Dispel Magic]] (3rd-rank; counteract DC 25); two total successes are required to deactivate the pool."
attacks:
  - name: ""

  - name: "Echoing Spring"
    desc: "`pf2:r` **Trigger** a creature within 10 feet can see or hear the cleansing pool\n* * *\n\n**Effect** each creature within range must succeed a `DC 25 Will check` save or become [[Conditions/Fascinated|Fascinated]], using all of their available actions to move toward and into the pool. The hazard then rolls initiative."

  - name: "Drown the Nonbelievers"
    desc: "`pf2:r` **Trigger** a [[Conditions/Fascinated|Fascinated]] creature enters the pool\n* * *\n\n**Effect** the waters rush up to encircle the creature, which must succeed on a `DC 25 Fortitude check` save or begin drowning."

  - name: "Routine"
    desc: "(1 action; mental) The cleansing pool uses its first action to try and compel all creatures within 5 feet to enter into the pool. Creatures must attempt a `DC 23 Will check` save.\n* * *\n\n**Critical Success** The creature is immune to the pool's routine for 1 minute.\n\n**Success** No effect.\n\n**Failure** The creature gains the [[Conditions/Fascinated|Fascinated]] condition and attempts to enter the pool.\n\n**Critical Failure** As failure, but the creature must also use all of their actions on their next turn to try and pull one of their allies into the pool with them."

```

```encounter-table
name: Scouring Pool
creatures:
  - 1: Scouring Pool
```

