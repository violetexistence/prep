---
title: "Ghoul Commando"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.pfs-season-6-bestiary.Actor.RqMuQNzW5qQ7elW8" 
tags:
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Ghoul Commando"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Society Scenario #6-99: Under the Eye of the Mantis"
name: "Ghoul Commando"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[ghoul]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +14, Stealth: +13, Survival: +11"
abilityMods: [4, 3, 2, 1, 2, 4]
speed: 25 feet,  burrow 5 feet
sourcebook: "_Pathfinder Society Scenario #6-99: Under the Eye of the Mantis_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +12, __Will__ +10"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+1 Striking Bastard Sword, Breastplate"
abilities_mid:
  - name: ""
  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Stench"
    desc: " (aura,olfactory) 10 feet, `DC 19 Fortitude check`\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (unarmed)\n__Damage__  1d10 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, unarmed)\n__Damage__  1d8 + 6 slashing plus *Grab*"

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+15 (magical, two-hand d12)\n__Damage__  2d8 + 4 slashing"

  - name: "Consume Flesh"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 3d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "Ghoul Whispers"
    desc: "`pf2:1` (auditory,linguistic,occult) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], or [[Conditions/Unconscious|Unconscious]] creature is within the ghoul's reach\n* * *\n\n**Effect** The ghoul whispers dark thoughts and vile cravings into the creature's ears. The creature must save against the forbidden cravings curse.\n\n**Forbidden Cravings** (curse) A creature can still eat and drink while sickened by this curse\n\n**Saving Throw** `DC 22 Will check`\n\n**Stage 1** carrier with no ill effects (1 day)\n\n**Stage 2** 2d6 void damage and the target is [[Conditions/Sickened|Sickened 1]] until it consumes raw meat (1 day)\n\n**Stage 3** as stage 2\n\n**Stage 4** as stage 2 unless the target has consumed raw meat in the past 24 hours, then it takes 4d6 void damage and is [[Conditions/Sickened|Sickened 2]] until it consumes raw meat;\n\n**Stage 5** if the creature has eaten raw meat in the past 24 hours, it dies and rises as a ghoul, if not, it returns to stage 4"

  - name: "Grave Knowledge"
    desc: " (occult) +13 skill modifier\n* * *\n\n**Frequency** once per hour\n* * *\n\n**Effect** The ghoul calls upon knowledge it retains from one creature it has consumed in the past 7 days. The ghoul attempts a skill check using a skill in which the consumed creature was trained (if it's unclear whether the creature was trained, the GM decides). The ghoul is treated as trained and uses the high skill modifier for the ghoul's level. This takes the same amount of actions or time as usual for the check.\n\nThe ghoul can instead automatically learn something specific known by a creature it consumed in the last 7 days, like the location of a [[Conditions/Hidden|Hidden]] treasure or the name of a loved one. The ghoul can do this only once for a given creature, no matter how much of its flesh the ghoul consumed."

  - name: "Swift Leap"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ghoul Commando
creatures:
  - 1: Ghoul Commando
```


Variant ghoul soldier

Retaining their martial skill, these powerful ghouls are not afraid to meet their foe in the open, feeding on the flesh of their fallen opponents to learn their combat abilities.

* * *

Few creatures are more ubiquitous to sinister locations such as lonely graveyards and ruined crypts than the flesh-eating undead known as ghouls.
