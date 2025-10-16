---
title: Ice Prison Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - cold
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #215: To Blot Out the Sun
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.Ic9RRSNlYOxCRxo7" 
level: 5
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Ice Prison Trap"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[cold]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 26
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
perception:
  - name: ""
  - name: "Stealth DC 26" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Magical sensors trigger clockwork cryomisters to expel frigid air, freezing intruders and potentially encasing them in a block of ice."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "`DC 22 Thievery check` (expert) to disable the cryomisters, or `DC 24 Arcana check` (expert) to trick the magical sensors, or [[Spells/Dispel Magic|Dispel Magic]] (3rd rank; counteract DC 24) to counteract the sensors"
attacks:
  - name: ""

  - name: "Cryo Mist"
    desc: "`pf2:r` **Trigger** A creature enters the area, and that creature is not a clockwork soldier and is not openly wearing a _security badge_\n* * *\n\n**Effect** The trap fills the area with frigid air, which deals 2d8+7 cold damage to creatures in the area (`DC 22 Fortitude check` save). Clockwork soldiers and any creatures openly wearing a _security badge_ are immune to this damage. The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) On its turn, the trap fills the area with frigid air, which deals 2d8+7 cold damage to creatures in the area. Creatures damaged must attempt a `DC 22 Fortitude check` save. Clockwork soldiers and any creatures wearing a security badge are immune to this damage. The accumulating ice causes the floor in the area to become difficult terrain that lasts for 1 minute after the trap's routine ends.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target takes half damage and increases its [[Conditions/Slowed|Slowed]] condition by 1.\n\n**Failure** The target takes full damage and increases its slowed condition by 1.\n\n**Critical Failure** The target takes double damage and increases its slowed condition by 2.\n* * *\n\nOnce a creature's actions are reduced to 0 by this slowed condition, the creature is completely encased in ice. The ice has Hardness 5 and 20 Hit Points, and its DC to [[Actions/Force Open|Force Open]] is DC 22. Breaking the ice frees the creature and reduces their slowed condition by 1. Each round a creature is encased in ice, they take 1d8+7 cold damage (`DC 22 Fortitude check` save)."
  - name: "Reset"
    desc: "The trap resets after 10 minutes."
```

```encounter-table
name: Ice Prison Trap
creatures:
  - 1: Ice Prison Trap
```

