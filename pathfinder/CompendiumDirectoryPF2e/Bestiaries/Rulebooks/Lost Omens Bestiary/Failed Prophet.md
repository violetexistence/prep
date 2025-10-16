---
title: "Failed Prophet"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.lost-omens-bestiary.Actor.37kLxtNV11aIPPja" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Failed Prophet"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens Shining Kingdoms"
name: "Failed Prophet"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Common, Dwarven"
skills:
  - name: "Skills"
    desc: "Diplomacy: +20, Occultism: +23, Thievery: +23, Mercantile Lore: +26"
abilityMods: [7, 3, 5, 5, 7, 6]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens Shining Kingdoms_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +17, __Will__ +23"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ spirit 10; __Resistances__ cold 10, electricity 10, physical 10 (except magical bludgeoning)"
abilities_top:
  - name: ""

  - name: "Wealthsense"
    desc: "  150 gp\n\nThe failed prophet can detect concentrations of coinage and other valuables as an imprecise sense with a range of 60 feet. The failed prophet detects any creature carrying coins and treasure totaling at least the average cost of a consumable item of the failed prophet's level."

abilities_mid:
  - name: ""
  - name: "Broken Mindscape"
    desc: " (aura,illusion,incapacitation,mental) 30 feet, `DC 27 Will check`.\n\nA creature entering the aura or starting its turn in the aura must attempt a Will save. Use the moderate spell DC for the failed prophet's level.\n* * *\n\n**Critical Success** The creature is unaffected and becomes immune to broken mindscape for 1 minute.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]] as disjointed visions of the failed prophet's mindscape assail its senses.\n\n**Failure** The creature's mind is pulled into the failed prophet's mindscape. It's [[Conditions/Paralyzed|Paralyzed]] for 1 round. While paralyzed, the creature can take any actions with the mental or spirit traits, or that deal mental or spirit damage, as though those actions were purely mental. Such actions only have line of effect to the originating failed prophet and other creatures currently paralyzed by broken mindscape, though they treat all such creatures as though they were adjacent.\n\n**Critical Failure** As failure, but the duration is 1 minute or until the failed prophet is destroyed, whichever happens first."

  - name: "Taboos"
    desc: "  Despite the failed prophet's transformed body, a lifelong adherence to the strictures of the Prophecies of Kalistrade has ingrained the philosophical prohibitions into their soul. Whenever a failed prophet is critically hit by an unarmed attack, is critically hit by or critically fails a save against a touch spell, or is exposed to a disease or poison effect (even though immune), they take a –2 status penalty to their AC, attack bonuses, DCs, Perception, saving throws, and skill modifiers for 1 minute. Breaking other Kalistocratic taboos can also trigger this penalty at the GM's discretion."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (magical, reach 10 feet)\n__Damage__  2d10 + 11 bludgeoning plus *greedy-grab*"

  - name: "Occult Spontaneous Spells"
    desc: "DC 27, attack +19; __5th __ (3 slots) _[[Spells/Invoke Spirits|Invoke Spirits]]_, _[[Spells/Shadow Blast|Shadow Blast]]_, _[[Spells/Telekinetic Haul|Telekinetic Haul]]_; __4th __ (4 slots) _[[Spells/Confusion|Confusion]]_, _[[Spells/Translocate|Translocate]]_, _[[Spells/Vision of Death|Vision of Death]]_; __3rd __ (4 slots) _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __ (4 slots) _[[Spells/Paranoia|Paranoia]]_, _[[Spells/Stupefy|Stupefy]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_; __1st __ (5 slots) _[[Spells/Ill Omen|Ill Omen]]_, _[[Spells/Item Facade|Item Facade]]_, _[[Spells/Phantasmal Minion|Phantasmal Minion]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Greedy Grab"
    desc: "`pf2:1`  **Requirements** The failed prophet's last action was a successful fist Strike that dealt damage\n* * *\n\n**Effect** The failed prophet attempts a Thievery check against the target's Reflex DC. On a success, the failed prophet pilfers coins and gems from the target with a total value as indicated in the table, to a maximum of what the target is carrying. Valuables in unlocked containers on the target's person can be taken just as easily as those carried. On a critical success, the failed prophet steals double that amount. The failed prophet gains a number of temporary Hit Points equal to the value stolen that last for 1 minute.\n\n  \n\n| Level | Value Stolen |\n| --- | --- |\n| 10–12 | 5d10 gp |\n| 13–15 | 6d10 gp |\n| 16–18 | 7d10 gp |\n| 19–20 | 8d10 gp |"

  - name: "This Is My Reality!"
    desc: "`pf2:2` (concentrate) 6d6 spirit, `DC 30 Will check`\n\nThe failed prophet exerts control over their crumbling mindscape to inflict harm upon those trapped within. This can take the form of falling debris, natural disasters, or anything else the failed prophet can imagine. No matter the form, each creature currently [[Conditions/Paralyzed|Paralyzed]] by the failed prophet's broken mindscape takes spirit damage with a basic Will save. The save DC uses the high spell DC for the failed prophet's level and the unlimited use area damage for the failed prophet's level."
 
```

```encounter-table
name: Failed Prophet
creatures:
  - 1: Failed Prophet
```



Following the teachings of Kalistrade is a lifelong commitment. It requires studious adherence to the strictures and taboos laid out in the Prophecies. The ultimate reward for the devout is the promise of a personalized afterlife, filled with a lifetime of wealth and free of Pharasma's judgment. Not all who learn of these final revelations are up to the task, however. For the fortunate ones, a simple death is the only consequence for botching the ritual. For the less fortunate, the outcome is an undying half-life of torment. Caught between a twisted mockery of their imagined afterlife and the mortal Universe, a failed prophet will know no peace until their body is destroyed.

A failed prophet resembles the skinless corpse of a humanoid ancestry covered in glowing, golden veinlike cracks. On closer inspection, the organs and musculature are unnaturally smooth and shiny, like cured and buffed leather.
