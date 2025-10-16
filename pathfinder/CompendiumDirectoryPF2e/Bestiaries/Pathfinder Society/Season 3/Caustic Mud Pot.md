---
title: Caustic Mud Pot
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - poison
  - pf2eHazard
  - complex
source: Pathfinder Society Scenario #3-10: Delve the Pallid Depths
aliases: "Compendium.pf2e.pfs-season-3-bestiary.Actor.vkrKdprKwRpuXHS3" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society Scenario #3-10: Delve the Pallid Depths"
name: "Caustic Mud Pot"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[poison]]
modifier: 11
sourcebook: "_Pathfinder Society Scenario #3-10: Delve the Pallid Depths_"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Solid ground gives way to a lake of bubbling mud that burns anyone who enters and routinely belches out sulfur."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "`DC 20 Survival check` (trained) to find and remove the stones blocking the flow of water to the mud pot. The water decreases the viscosity of the mud, allowing steam and sulfur to escape gradually, rather than in violent bursts, so creatures can pass through unharmed. The hazard requires one successful checks to disable. Attempting the check takes two actions."
attacks:
  - name: ""

  - name: "Belch"
    desc: "`pf2:r` **Trigger** A creature other than a sulfuric slime comes within 10 feet of the mud pot\n* * *\n\n**Effect** The hazard rolls initiative as a gaseous cloud explodes out of the mud. The triggering creature takes 1d10+6 acid damage `DC 20 Reflex check`"

  - name: "Sulfur Poisoning"
    desc: "passive (poison) **Saving Throw** `DC 17 Fortitude check`\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d10 poison damage\n\n**Stage 2** 1d12 poison damage and [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Sickened|Sickened2]] (1 round)"

  - name: "Routine"
    desc: "(1 action) On its initiative, the mud pot belches a cloud of sickening sulfur into the small cavern. Creatures other than sulfuric slimes within 10 feet must succeed at a `DC 17 Fortitude check` save or be exposed to sulfur poisoning."

```

```encounter-table
name: Caustic Mud Pot
creatures:
  - 1: Caustic Mud Pot
```

