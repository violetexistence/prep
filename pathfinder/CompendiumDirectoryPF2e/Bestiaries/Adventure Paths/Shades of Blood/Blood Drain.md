---
title: Blood Drain
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #215: To Blot Out the Sun
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.Yu7M6YN9qNan0Dyt" 
level: 6
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Blood Drain"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A tiny spark of Nin's will drains the blood from living intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "`DC 26 Thievery check` (expert) to vandalize the space, or `DC 24 Religion check` (expert) to pray to a god for passage, or [[Spells/Dispel Magic|Dispel Magic]] (3rd rank; counteract DC 25) to counteract the magical energy"
attacks:
  - name: ""

  - name: "Drain Blood"
    desc: "`pf2:r` (divine, void) **Trigger** A living creature enters the room of their own accord\n* * *\n\n**Effect** The trap drains the blood from all living creatures in the room, which manifests as a bloody mist in the air. All living creatures in the room are dealt 2d6+8 void damage (`DC 26 Fortitude check` save). On a failure, a creature increases the value of their drained condition by 1. The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) On its initiative, the trap continues to drain blood, dealing 2d6+8 void damage to all living creatures in the room (`DC 26 Fortitude check` save). On a failure, a creature increases the value of their drained condition by 1."
  - name: "Reset"
    desc: "The trap automatically deactivates after 1 minute. It resets in 1 hour."
```

```encounter-table
name: Blood Drain
creatures:
  - 1: Blood Drain
```

