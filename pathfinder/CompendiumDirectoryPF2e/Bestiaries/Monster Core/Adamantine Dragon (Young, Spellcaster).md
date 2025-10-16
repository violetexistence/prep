---
title: "Adamantine Dragon (Young, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-monster-core.Actor.YV83qiV7nEtVDPEP" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/primal
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Adamantine Dragon (Young, Spellcaster)"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Adamantine Dragon (Young, Spellcaster)"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[primal]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 60 Feet"
languages: "Common, Draconic, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +21, Intimidation: +18, Nature: +17, Survival: +19, Mining Lore: +16"
abilityMods: [6, 2, 4, 1, 2, 3]
speed: 25 feet,  burrow 30 feet,  fly 90 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +15, __Will__ +17; +2 status to all saves vs primal"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  paralyzed,  petrified,  sleep; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Abandon Armor"
    desc: "  Once the adamantine dragon is reduced to fewer than half their Hit Points, their resistance is reduced by 10 and they gain a +10 circumstance bonus to their Speeds."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet `DC 26 Will check`\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Resilient Form"
    desc: "`pf2:r`  **Trigger** The dragon is critically hit with a weapon or unarmed attack;\n* * *\n\n**Effect** The dragon's tough scales ward off deadly attacks. The dragon attempts a `DC 17 Flat check`. On a success, the triggering attack becomes a normal hit."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (magical, reach 10 feet, unarmed, adamantine)\n__Damage__  2d12 + 9 piercing plus *Grab*"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, magical, unarmed, adamantine)\n__Damage__  2d8 + 9 slashing plus *Knockdown*"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 (magical, reach 15 feet, adamantine)\n__Damage__  2d10 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+19 (brutal, range increment 90 feet)\n__Damage__  2d8 + 9 bludgeoning"

  - name: "Primal Prepared Spells"
    desc: "DC 28, attack +21; __4th __  _[[Spells/Shape Stone|Shape Stone]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_; __3rd __  _[[Spells/Earthbind|Earthbind]]_, _[[Spells/One with Stone|One with Stone]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Shatter|Shatter]]_, _[[Spells/Water Walk|Water Walk]]_; __1st __  _[[Spells/Air Bubble|Air Bubble]]_, _[[Spells/Tailwind|Tailwind]]_, _[[Spells/Vanishing Tracks|Vanishing Tracks]]_\n__Cantrips__  __(4th)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Sigil|Sigil]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Adamantine Body"
    desc: "  The dragon's unarmed melee Strikes are adamantine."

  - name: "Avalanche Breath"
    desc: "`pf2:2` (primal) The dragon belches a mass of boulders that deals 8d8 bludgeoning damage in a 30-foot cone (`DC 28 Reflex check` save).\n\nThey can't use Avalanche Breath again for 1d4 rounds."

  - name: "Burrowing Pounce"
    desc: "`pf2:3`  **Requirements** The dragon is burrowed\n* * *\n\n**Effect** The dragon Burrows, then Leaps out of the ground, landing at a point within 25 feet. The dragon makes a melee Strike against a creature within reach when they land. If the Strike is a critical hit, the target is knocked [[Conditions/Prone|Prone]]."

  - name: "Rock Tunneler"
    desc: "  The dragon can burrow through solid stone at a Speed of 20 feet. They can leave a tunnel if they desire, and they usually don't."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d12+4 bludgeoning, Rupture 22\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an `Athletics check` check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\n[[Bestiary Effects/Effect_ Engulf and Swallow Whole|Effect: Engulf and Swallow Whole]]\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/trip|trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Adamantine Dragon (Young, Spellcaster)
creatures:
  - 1: Adamantine Dragon (Young, Spellcaster)
```



The powerful adamantine dragons are one of several dragons known as skymetal dragons. The innate magic that flows through these dragons causes them to draw particular metals to their bodies like magnets or, in some cases, naturally grow these skymetals on their bodies. Adamantine dragons begin their lives with tough scales that are naturally replaced with thicker and even tougher adamantine plating as they grow older. Adamantine dragons are typically steadfast and loyal. Once they commit to a certain purpose, changing their minds is nigh impossible.

* * *

Dragons come in myriad forms, with many having magical abilities or connections to magic. Some dragons draw greater power from magic than others, allowing them to manifest abilities or alter their physiques with prolonged exposure to magic. These dragons become more powerful as they age and strengthen their connections with their magical origins. Scholars debate the classification of these dragons, with some preferring the name magical dragons and others using traditional dragons due to their connection to specific magical traditions. Regardless of their names, these dragons share a number of characteristics: their ability to tap into magical energies, intensified might and cunning as they grow older, and an inclination to hoard vast amounts of treasure and wealth.

## Draconic Spellcasters

Each dragon features a sidebar on spellcasting dragons of that type. To make a dragon spellcaster, remove the dragon's Draconic Frenzy and Draconic Momentum abilities, and give them the spells outlined in their sidebar. You can swap out any number of these with other spells, provided you keep the same number of spells for each rank. You might also want to increase the dragon's Intelligence, Wisdom, or Charisma modifier by 1 or 2 to reflect their mastery of magic.
