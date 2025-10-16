---
title: Acid Mist
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #215: To Blot Out the Sun
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.0hKpSwWOIMDURHXe" 
level: 6
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Acid Mist"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +17, __Ref__ +11, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56; __Hardness__ 13; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A golden guardrail sprays magical, flesh-eating acid throughout the stairwell."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "`DC 26 Thievery check` (expert) to deactivate the trap's sensors, or `DC 24 Arcana check` (expert) to disrupt the guardrail's magic, or [[Spells/Dispel Magic|Dispel Magic]] (3rd rank; counteract DC 24) to counteract the guardrail"
attacks:
  - name: ""

  - name: "Spray Acid"
    desc: "`pf2:r` (acid, arcane) **Trigger** A creature steps on the south stairs\n* * *\n\n**Effect** The guardrail sprays flesh-eating acid, filling the entire stairwell. All living creatures on the stairs area take 2d8+9 acid damage (`DC 27 Reflex check` save). The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) On its initiative, the trap continues to spray acid, dealing 2d8+9 acid damage to all living creatures on the stairs (`DC 25 Reflex check` save)."
  - name: "Reset"
    desc: "The trap automatically deactivates after 1 minute. It resets in 1 hour."
```

```encounter-table
name: Acid Mist
creatures:
  - 1: Acid Mist
```

