---
title: "Clockwork Corpse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.to8imCECPsArwlE2" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Clockwork Corpse"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Clockwork Corpse"
level: "Creature 5"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +12, Stealth: +11"
abilityMods: [5, 2, 4, -5, -1, -1]
speed: 20 feet
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +15, __Ref__ +11, __Will__ +8"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 5, orichalcum 5, vitality 5; __Resistances__ physical 5 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, [[Actions/disable-device dc=20|disable-device dc=20]], standy\n\nUnlike most clockworks, when a clockwork corpse has 0 operational time remaining, rather than shut down, it instead becomes [[Conditions/Slowed|Slowed 1]] and can't use reactions. These conditions are removed when its wound.\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm Blade"
    desc: "+15 (versatile s)\n__Damage__  2d10 + 7 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+15 (agile, unarmed)\n__Damage__  2d6 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Festering Fluid"
    desc: "+12 (range increment 30 feet)\n__Damage__  3d6 poison"

  - name: "Pressurized Blast"
    desc: "`pf2:2`  With a whir of clockwork mechanisms, spinning gears, and grinding bones, the clockwork corpse opens its torso and disgorges a pressurized spray of festering internal fluids and caustic oil in a 30-foot line. Creatures in the area are dealt 3d6 bludgeoning damage and 3d6 poison damage (`DC 22 Reflex check` save). On a critical failure, a creature is additionally knocked [[Conditions/Prone|Prone]] by the force. The clockwork corpse can't use Pressurized Blast again for 1d4 rounds."
 
```

```encounter-table
name: Clockwork Corpse
creatures:
  - 1: Clockwork Corpse
```




