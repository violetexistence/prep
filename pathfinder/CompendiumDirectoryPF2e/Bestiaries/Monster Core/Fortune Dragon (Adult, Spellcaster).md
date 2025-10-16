---
title: "Fortune Dragon (Adult, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-monster-core.Actor.ED9YZQYMGHuN5l8E" 
tags:
  - pf2e/creature/type/arcane
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Fortune Dragon (Adult, Spellcaster)"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Fortune Dragon (Adult, Spellcaster)"
level: "Creature 14"

alignment: ""
size: "huge"
trait_01: [[arcane]]
trait_02: [[dragon]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Dwarven"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Arcana: +28, Athletics: +27, Crafting: +28, Diplomacy: +24, Thievery: +27, Accounting Lore: +28, Mercantile Lore: +28"
abilityMods: [7, 7, 6, 8, 4, 4]
speed: 70 feet,  fly 140 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +27, __Will__ +24; +2 status to all saves vs. arcane"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Immunities__  drained,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Aura of Disruption"
    desc: " (arcane,aura) 120 feet.\n\nThe dragon radiates disruptive energies that allow them to feed on magic. When a spell is counteracted or disrupted within the aura, the dragon regains one expended spontaneous spell slot and gains 25 temporary Hit Points that last for 1 minute."

  - name: "Capture Spell"
    desc: "`pf2:r` (arcane) **Trigger** The dragon succeeds or critically succeeds on a saving throw against a spell\n* * *\n\n**Effect** The dragon attempts to capture a portion of the spell's magic to feed themself. They attempt to counteract the spell (counteract rank 7, counteract modifier +28). If successful, the dragon is unaffected by the spell and regains one expended spontaneous spell slot; other subjects are affected by the spell normally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (magical, reach 15 feet, unarmed)\n__Damage__  3d10 + 13 piercing 1d6 force"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, magical, reach 10 feet, unarmed)\n__Damage__  1d6 force 3d6 + 13 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+25 (magical, reach 20 feet)\n__Damage__  1d6 force 3d10 + 13 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 36, attack +28; __6th __  _[[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]_, _[[Spells/Teleport|Teleport]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __  _[[Spells/Howling Blizzard|Howling Blizzard]]_, _[[Spells/Scouting Eye|Scouting Eye]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_; __4th __  _[[Spells/Flicker|Flicker]]_, _[[Spells/Translocate|Translocate]]_, _[[Spells/Vision of Death|Vision of Death]]_; __3rd __  _[[Spells/Aqueous Orb|Aqueous Orb]]_, _[[Spells/Haste|Haste]]_; __2nd __  _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Mist|Mist]]_, _[[Spells/Web|Web]]_; __1st __  _[[Spells/Grease|Grease]]_, _[[Spells/Gust of Wind|Gust of Wind]]_, _[[Spells/Item Facade|Item Facade]]_, _[[Spells/Phantasmal Minion|Phantasmal Minion]]_\n__Cantrips__  __(7th)__ _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 36, attack +22; __7th __ (2 slots) _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Slither|Slither]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_, _[[Spells/Warp Mind|Warp Mind]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Read Aura|Read Aura]]_"

  - name: "Disruptive Breath"
    desc: "`pf2:2` (arcane,force) The dragon unleashes a spray of magic-disrupting energies that deals 13d6 force damage in a 40-foot cone (`DC 36 Reflex check` save). Creatures that fail become [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Stupefied|Stupefied 2]] on a critical failure) for 1 minute.\n\nThe dragon can't use Disruptive Breath again for 1d4 rounds."

  - name: "Share the Wealth"
    desc: "`pf2:2`  **Requirements** The dragon's body is covered in riches (this is typically the case when the dragon is first encountered)\n* * *\n\n**Effect** The dragon shakes their body aggressively, sending coins and other riches flying in every direction, dealing 9d10 bludgeoning damage with a `DC 35 Reflex check` save to all creatures in a 40-foot emanation. The dragon's body is then no longer covered in riches."

  - name: "Treasure Dive"
    desc: "`pf2:2`  **Requirements** The dragon's body isn't covered in riches and the dragon is adjacent to their hoard\n* * *\n\n**Effect** The dragon Strides or Burrows through their hoard using their land Speed. They coat themself in coins, magic items, and other treasures. This contact with magical items revitalizes the dragon, causing them to regain one expended spontaneous spell slot.\n\nThe dragon can move through other creatures while moving in this way. Creatures in the dragon's path, or above it if the dragon Burrows, must succeed at a `DC 33 Reflex check` save or be pushed 10 feet (or pushed 20 feet and knocked [[Conditions/Prone|Prone]] on a critical failure)."
 
```

```encounter-table
name: Fortune Dragon (Adult, Spellcaster)
creatures:
  - 1: Fortune Dragon (Adult, Spellcaster)
```



Fortune dragons have the innate ability to draw upon the raw magical energies that surround them. They constantly use these magical energies to empower their magical abilities and even their bodies, as the energy can heal wounds. A fortune dragon has a typical build for an arcane dragon, but their bodies sport a striking feature: their treasure. The dragon's nature of drawing upon magic causes coins, gems, and, most notably, magical items to cling to their body like iron drawn to magnets. A dragon constantly pulls magical energies from the items attached to their body and makes use of these energies to cast spells. The magical energies that flow through a fortune dragon constantly flow through the dragon's items as well, and in many cases, the items melt from the heat produced in this process. Fortune dragons are seekers of novel experiences. This desire for originality leads fortune dragons to approach visitors of other ancestries with curiosity, though this initial interest quickly wanes if a visitor lacks exciting qualities.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
