---
title: "Lamp Blighter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.lost-omens-bestiary.Actor.9DeZiBTu0jJNLyN3" 
tags:
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Lamp Blighter"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens Shining Kingdoms"
name: "Lamp Blighter"
level: "Creature 6"

alignment: ""
size: "Small"
trait_01: [[fey]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Deception: +13, Intimidation: +13, Nature: +13, Stealth: +15"
abilityMods: [1, 5, 1, 2, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens Shining Kingdoms_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +11, __Ref__ +17, __Will__ +14; +1 status to all saves vs. magic"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  blinded; __Weaknesses__ cold iron 5, fire 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+1 Shortbow, 60x Arrows"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, finesse, magical)\n__Damage__  2d4 + 7 slashing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+17 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 6 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 24, attack +16; __4th __  _[[Spells/Darkness|Darkness]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Dispel Magic|Dispel Magic]]_; __2nd __  _[[Spells/Floating Flame|Floating Flame]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Ignition|Ignition]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Shield|Shield]]_"

  - name: "Eye Pluck"
    desc: "`pf2:1` (manipulate) **Frequency** once per round\n\n**Requirements** The lamp blighter's last action was a successful claw Strike against a creature with eyes\n* * *\n\n**Effect** The lamp blighter attempts to pluck out one of the required creature's eyes. The target must attempt a `DC 21 Fortitude check` save. On a failure, the target takes 4 persistent bleed damage and is [[Conditions/Dazzled|Dazzled]] for 1 round. On a critical failure, the target's eye is also severely damaged, taking a –4 circumstance penalty on all sight-based Perception checks until the target returns to full Hit Points or the wound is otherwise healed (by magic such as [[Spells/Sound Body|Sound Body]] or [[Spells/Regenerate|Regenerate]]). If all a creature's eyes are severely damaged in this way, that creature is [[Conditions/Blinded|Blinded]] for the same duration.\n\n[[Bestiary Effects/Effect_ Eye Pluck|Effect: Eye Pluck]]"

  - name: "Fear the Darkness"
    desc: "`pf2:2` (concentrate,emotion,fear,mental,primal) **Requirements** The lamp blighter must be in an area of darkness\n* * *\n\n**Effect** The lamp blighter evokes the terror of being unable to see in the dark. Each creature within a 20-foot emanation that doesn't have darkvision must succeed at a `DC 23 Will check` save or become [[Conditions/Frightened|Frightened 2]]."

  - name: "Snuff the Light"
    desc: "`pf2:1` (concentrate,fire,primal) The lamp blighter extinguishes light sources in a 10-foot emanation. They extinguish all non-magical light sources automatically and attempt to extinguish magical light sources with a +16 counteract modifier and a counteract rank of 3. If the lamp blighter successfully extinguishes any light, their next successful claw or shortbow Strike deals 1d6 persistent fire damage."
 
```

```encounter-table
name: Lamp Blighter
creatures:
  - 1: Lamp Blighter
```




