---
title: "Raised Cavalry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.claws-of-the-tyrant-bestiary.Actor.vdywUTHF4uhA7cyh" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
  - remaster
statblock: inline
name: "Raised Cavalry"
level: 19
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Claws of the Tyrant"
name: "Raised Cavalry"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[mindless]]
trait_02: [[troop]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +37"
abilityMods: [10, 5, 6, 5, 6, 6]
speed: 40 feet
sourcebook: "_Pathfinder Claws of the Tyrant_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +29, __Ref__ +28, __Will__ +31"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360, Thresholds 360 (4 segments), 240 (3 segments), 140 (2 segments); __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ area damage 20, splash damage 20, vitality 20; __Resistances__ physical 20"
abilities_top:
  - name: ""

  - name: "Darkvision"
    desc: "  A monster with darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. Some forms of magical darkness, such as a 4th-rank [[Spells/Darkness|Darkness]] spell, block normal darkvision. A monster with [[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]], however, can see through even these forms of magical darkness."

  - name: "Mounted"
    desc: "  When not mounted, the raised cavalry is slowed 1."

abilities_mid:
  - name: ""
  - name: "Shuffle Forces"
    desc: "  The raised cavalry consists of skeletons, zombies, and other undead hastily bound to a shared cause. The cavalry has resistance 20 to physical damage, as it shuffles its weakest members to the front lines. When the cavalry is reduced to 12 squares or fewer, its resistance to physical drops to 10. Once the cavalry reaches the 2-segment threshold, it loses its resistance to physical damage."

  - name: "Troop Defenses"
    desc: "  **Thresholds** 360 (4 segments), 240 (3 segments), 140 (2 segments)\n* * *\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Claws and Jaws"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** Members of the cavalry leap from their mounts and attack each enemy within 10 feet (`DC 41 Reflex check` save).\n\nThe damage depends on the number of actions.\n\n`pf2:1` 2d12+14 piercing and slashing plus 1d12 void\n\n`pf2:2` 3d12+14 piercing and slashing plus 1d12 void\n\n`pf2:3` 4d12+14 piercing and slashing plus 1d12 void"

  - name: "Hail of Arrows"
    desc: "`pf2:2`  Members of the raised cavalry draw or reload their shortbows, then launch a ranged attack in the form of a volley. This volley is a 10-foot burst within 60 feet that deals 7d8 piercing damage (`DC 41 Reflex check` save). When the cavalry is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Trampling Charge"
    desc: "`pf2:2`  The raised cavalry Strides twice with a +10-foot circumstance bonus to its Speed. During this movement, the cavalry can move through the spaces of Medium or smaller creatures. It deals 3d12+14 bludgeoning damage to each creature whose space it moves through (`DC 41 Reflex check` save). A creature that fails its save is also knocked [[Conditions/Prone|Prone]]. The cavalry can affect the same creature only once in a single use of Trampling Charge."
 
```

```encounter-table
name: Raised Cavalry
creatures:
  - 1: Raised Cavalry
```



Undead are plentiful throughout the Gravelands, but even so, necromancers must sometimes get creative to organize the varied undead they have on hand into a cohesive military unit. While the typical raised cavalry is a mix of skeletons, zombies, and ghouls, many units also incorporate mummies, ghosts, and more powerful undead.

The Knights of Lastwall have reported battalions of undead rising from the fields where they were buried, presumably in preparation for a future assault. One of the most infamous of these staging grounds was Fallowdeep, the network of subterranean tunnels beneath the former dwarven fortress of Hammer Rock. When the Whispering Tyrant attacked the nations of the Inner Sea, Fallowdeep's supply of undead was vastly depleted, but caches of corpses no doubt remain there for a resourceful necromancer to exploit.
