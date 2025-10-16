---
title: "Corbayrant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.lost-omens-bestiary.Actor.TRmzCBwEeJFqiQ3D" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fey
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Corbayrant"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens Shining Kingdoms"
name: "Corbayrant"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[fey]]
trait_03: [[plant]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; "
languages: "Common, Fey, Muan"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Nature: +29, Stealth: +27, Survival: +27"
abilityMods: [9, 5, 6, 4, 5, 1]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder Lost Omens Shining Kingdoms_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +30, __Ref__ +27, __Will__ +27"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  blinded,  visual; __Weaknesses__ cold 15; __Resistances__ fire 10, piercing 15"
abilities_top:
  - name: ""

  - name: "Vitriolic Miasma"
    desc: " (aura) 30 feet.\n\nNon-corbayrants take a –2 circumstance penalty to saves against poison effects and gain weakness 10 to poison damage while within the aura."

abilities_mid:
  - name: ""
  - name: "Regeneration 20 (deactivated by cold)"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within your reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\nYou lash out at a foe that leaves an opening. Make a melee Strike against the triggering creature. If your attack is a critical hit and the trigger was a manipulate action, you disrupt that action. This Strike doesn't count toward your multiple attack penalty, and your multiple attack penalty doesn't apply to this Strike."

  - name: "Thorny Hide"
    desc: "  A corbayrant's body is covered in jagged spines. Adjacent creatures that hit them with a melee attack, as well as creatures that touch them or hit them with an unarmed attack, take 4d6 piercing damage and are exposed to thorn paralysis."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+32 ()\n__Damage__  3d12 + 18 piercing plus *Grab*"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+32 (reach 15 feet)\n__Damage__  3d10 + 15 piercing plus *corbayrant-venom*"

  - name: "**Ranged** `pf2:1` Spine"
    desc: "+32 (propulsive, range increment 40 feet)\n__Damage__  3d6 + 15 piercing plus *thorn-paralysis*"

  - name: "Corbayrant Venom"
    desc: "  **Saving Throw** `DC 37 Fortitude check`\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 8d6 poison damage (1 round)\n\n**Stage 2** 9d6 poison damage (1 round)\n\n**Stage 3** 9d6 poison damage and [[Conditions/Drained|Drained 1]] (1 round)"

  - name: "Spine Volley"
    desc: "`pf2:2`  The corbayrant makes four spine Strikes, each against a different target. These attacks all count toward the corbayrant's multiple attack penalty, but the penalty doesn't increase until after the corbayrant makes their attacks."

  - name: "Swallow Whole"
    desc: "`pf2:1` (attack) Large, 9d6 piercing plus thorn paralysis, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an `Athletics check` check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\n[[Bestiary Effects/Effect_ Engulf and Swallow Whole|Effect: Engulf and Swallow Whole]]\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thorn Paralysis"
    desc: " (incapacitation,poison) The corbayrant's spines are covered in a paralyzing toxin that cause verdurous thorns to sprout from their victim's body. When a non-corbayrant creature is exposed, it attempts a `DC 37 Fortitude check` save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature sprouts spines like those of the corbayrant. For 1 minute, the creature gains the corbayrant's thorny hide ability. Allies attempting to aid the victim with touch-range spells and abilities run the risk of becoming infected themselves. At the end of the duration, the spines fall off harmlessly.\n\n**Failure** As success, but the creature is also [[Conditions/Paralyzed|Paralyzed]] for 1 minute. It can attempt another Fortitude save at the end of each turn to end the paralysis, but not the spines.\n\n**Critical Failure** As failure, but the creature doesn't receive a save at the end of its turn to end the paralysis."
 
```

```encounter-table
name: Corbayrant
creatures:
  - 1: Corbayrant
```



Corbayrants are creations of the Green Mother, one of the fey called the Eldest. In the Age of Creation, she fashioned them from thorns and moss into deadly predators. When gnomes migrated to the mortal Universe, many corbayrants followed but found themselves poorly suited to life outside the First World.

Corbayrants are historically solitary, territorial creatures. They're incapable of reproducing, and without the revivifying properties of the First World, their numbers are doomed to deplete. Recently, a number of corbayrants in the Verduran Forest have overcome their natures to band together. They've been known to take their prey alive, sacrificing their victims in vile experiments in an effort to find a way to propagate corbayrant numbers.

Corbayrants look like massive clawless scorpions covered in bark and thorns. A rotting fog wafts from their bodies. In the rare instance when they deign to speak, they do so in a raspy whisper.
