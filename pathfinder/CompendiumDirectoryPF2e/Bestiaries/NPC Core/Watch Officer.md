---
title: "Watch Officer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pathfinder-npc-core.Actor.thDJ5N0wUvI1JOa6" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Watch Officer"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder NPC Core"
name: "Watch Officer"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Diplomacy: +6, Intimidation: +9, Society: +5, Legal Lore: +7"
abilityMods: [4, 1, 3, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder NPC Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19 (21 with shield raised); __Fort__ +10, __Ref__ +6, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Dagger|Dagger]], [[Equipment/Warhammer|Warhammer]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Breastplate|Breastplate]], [[Equipment/Signal Whistle|Signal Whistle]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Air of Authority"
    desc: " (aura,emotion,mental) 10 feet. Creatures in the aura who are the same or lower level than the watch officer take a -2 status penalty to their Will DC against the watch officer's attempts to [[Actions/coerce|coerce]] or [[Actions/demoralize|demoralize]] them."

  - name: "Bravery"
    desc: "  When the watch officer rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+13 (shove)\n__Damage__  1d8 + 7 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+10 (range increment 120 feet, reload 1)\n__Damage__  1d8 + 3 piercing"

  - name: "Sudden Charge"
    desc: "`pf2:2`  **Frequency** once per round\n* * *\n\n**Effect** The watch officer Strides twice. If they end their movement within melee reach of at least one enemy, they can make a melee Strike against that enemy."
 
```

```encounter-table
name: Watch Officer
creatures:
  - 1: Watch Officer
```



Often leading a small team of lower-ranking guards, watch officers patrol their assigned areas to maintain order and enforce laws. Watch officers get the job done, though their methods aren't always gentle or kind.

* * *

Larger societies rely on those with the authority and the ability to interpret and enforce laws. Some carry out these duties fairly, but others are harsh and cruel, imposing severe punishments on anyone unable to pay for clemency.
