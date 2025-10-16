---
title: "Clockwork Sentry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.n7NcIxT3kfhZjDL1" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Clockwork Sentry"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Clockwork Sentry"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, See the Unseen"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [6, 3, 4, -5, 4, -5]
speed: 25 feet
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +13, __Will__ +16"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 10, orichalcum 10; __Resistances__ physical 10 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "6x [[Equipment/Manacles (Average)|Manacles (Average)]]"
  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, [[Actions/disable-device dc=26|disable-device dc=26]], standy\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Sudden Seize"
    desc: "`pf2:r`  **Trigger** A creature within a clockwork sentry's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a space during a move action it's using\n* * *\n\n**Effect** The clockwork sentry makes an Athletics check to [[Actions/Grapple|Grapple]] the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pneumatic Swing"
    desc: "+20 (magical, reach 10 feet)\n__Damage__  2d10 + 10 bludgeoning plus *Knockdown*"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, nonlethal, reach 10 feet, unarmed)\n__Damage__  2d6 + 10 bludgeoning plus *Grab*"

  - name: "**Ranged** `pf2:1` Pulse Blast"
    desc: "+17 (range increment 100 feet)\n__Damage__  3d6 force plus *Push*"

  - name: "Arcane Innate Spells"
    desc: "DC 23, attack +15; __5th __  _[[Spells/Wall of Stone|Wall of Stone]]_; __4th __  _[[Spells/Sleep|Sleep]]_; __3rd __  _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_; __1st __  _[[Spells/Grease|Grease]]_\n__Constant__  __(2nd)__ _[[Spells/See the Unseen|See the Unseen]]_"

  - name: "Arrest"
    desc: "  **Trigger** The clockwork sentry has a creature [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The clockwork sentry Interacts to place manacles on the restrained creature."

  - name: "Tackle"
    desc: "`pf2:2`  The clockwork sentry Strides up to twice its Speed in a straight line. If it ends this movement in reach of a creature, it makes a fist Strike against that creature. On a hit or critical hit, the target takes an additional 1d6 bludgeoning damage and is knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/trip|trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Clockwork Sentry
creatures:
  - 1: Clockwork Sentry
```



Clockworks are intricate, complex machines built by talented engineers and infused with magical energy. At the height of the Azlanti Empire, magitech clockworks were commonplace, from music boxes, toys, and vehicles, to bodyguards, soldiers, spies, and even nannies.

Clockwork sentries are four-armed constructs created to serve as guardians, programmed either to prevent access to a specific location or to keep targets from escaping a secured site. This makes them the perfect clockwork for serving in prisons, dungeons, vaults, and similar locations.

## Winding Clockworks

A clockwork must be wound to remain operational. Each clockwork has the wind-up ability, with the specifics listed in its stat block. There are winding station locations in the adventure where a clockwork can return to be wound rather than having to rely upon another creature. The full rules for winding clockworks can be found in Pathfinder Bestiary 3 on page 48.

## Clockwork Hot Spots

Today, the nations of Alkenstar and New Thassilon, the church of Brigh, and the famed Clockwork Cathedral of Absalom are the primary sources for clockwork creation. Haunted clockworks from the Clicking Caverns often invade the nations of Nagajor and Xa Hoi.
