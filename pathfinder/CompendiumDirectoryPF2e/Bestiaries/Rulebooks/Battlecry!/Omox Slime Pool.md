---
title: "Omox Slime Pool"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.JLIdUna25mDtAdLM" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/ooze
  - pf2e/creature/type/troop
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Omox Slime Pool"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Omox Slime Pool"
level: "Creature 17"

alignment: ""
size: "grg"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[ooze]]
trait_04: [[troop]]
trait_05: [[unholy]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; "
languages: "Chthonian, Draconic, Empyrean; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +33, Religion: +28, Stealth: +36"
abilityMods: [9, 6, 9, 2, 4, 4]
speed: 40 feet,  climb 20 feet,  swim 80 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +32, __Ref__ +29, __Will__ +26"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315, 4 segments); Thresholds 210 (3 segments), 105 (2 segments); __Immunities__  acid,  critical hits,  disease,  poison,  precision; __Weaknesses__ area damage 15, splash damage 15, cold iron 15, holy 15"
abilities_top:
  - name: ""

  - name: "Clean Vulnerability"
    desc: "  Omoxes embody filth, and they find the concept of cleanliness abhorrent. An omox slime pool subjected to an effect that cleans them takes 4d6 mental damage. They also take this damage the first time each round a creature damaged by an omox slime pool spends actions cleaning off the resultant filth."

abilities_mid:
  - name: ""
  - name: "Absorb Weapon"
    desc: "`pf2:r` (concentrate) **Trigger** A creature hits the omox slime pool with a melee weapon\n* * *\n\n**Effect** The omoxes attempt to [[Actions/disarm|disarm]] the creature. On a critical success, the weapon becomes subsumed within the body of an omox rather than falling to the ground. Retrieving the weapon requires a successful [[Actions/disarm dc=45|disarm dc=45]]{DC 45 Athletics} check to Disarm."

  - name: "Troop Defenses"
    desc: "  **HP** 315 (4 segments); **Thresholds** 210 (3 segments), 105 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +0; __8th __  _[[Spells/Toxic Cloud|Toxic Cloud]]_; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Create Water|Create Water (At Will)]]_, _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Slime Barrage"
    desc: "`pf2:2`  The omoxes hurl balls of heavy slime in a 10-foot burst within 30 feet. All creatures in the area take 4d6 bludgeoning damage and 2d6 acid damage (`DC 35 Reflex check` save). A creature that fails the save is mired in the slime, taking a –10-foot circumstance penalty to its Speeds for 1 minute or until it Escapes ([[Actions/escape dc=38|escape dc=38]]{DC 38}); on a critical failure, the creature is also [[Conditions/Clumsy|Clumsy 1]] for the same duration. When the slime pool is reduced to 2 segments, the area decreases to a 5-foot burst."

  - name: "Smothering Grasp"
    desc: "`pf2:1`  **Requirements** The omox slime pool has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** Omox slime flows onto the creature, completely covering it. The creature must then succeed at a `DC 38 Fortitude check` save or it becomes [[Conditions/Blinded|Blinded]] and must hold its breath or begin [[PF2e Journals/GM Screen/suffocating|suffocating]]. These effects last as long as the omoxes have the creature grabbed or restrained.\n\n[[Other Effects/Effect_ Remaining Air|Effect: Remaining Air]]"

  - name: "Waves of Sludge"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The omoxes attack all enemies in a 5-foot emanation with slimy tendrils (`DC 35 Reflex check` save). A creature that critically fails this saving throw is also [[Conditions/Grabbed|Grabbed]] by the slime pool. The damage depends on the number of actions.\n\n`pf2:1` 1d6+3 bludgeoning damage plus 1d6 acid damage\n\n`pf2:2` 3d6+12 bludgeoning damage plus 2d6 acid damage\n\n`pf2:3` 4d6+14 bludgeoning damage plus 3d6 acid damage"
 
```

```encounter-table
name: Omox Slime Pool
creatures:
  - 1: Omox Slime Pool
```



Omoxes are the embodiment of pollution and filth. While they have no true anatomy, they tend to take on mocking humanoid forms—though this distinction is difficult to spot when omoxes gather in large groups as part of an attacking force. Such a group often looks like a single roiling mass of slime with multiple torsos jutting up in a military formation.
