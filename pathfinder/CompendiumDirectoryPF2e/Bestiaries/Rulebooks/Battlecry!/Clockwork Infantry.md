---
title: "Clockwork Infantry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.DFKYnBWjZ1i9Lssz" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Clockwork Infantry"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Clockwork Infantry"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
trait_04: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23"
abilityMods: [7, 3, 5, -5, 5, -5]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +21, __Will__ +18"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195, (4 segments); Thresholds 130 (3 segments), 65 (2 segments); __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 10, electricity 10, splash damage 10, orichalcum 10; __Resistances__ physical 5 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "Wind-Up"
    desc: "  24 hours, [[Actions/disable-device dc=27|disable-device dc=27]], standy\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Reactive Sweep"
    desc: "`pf2:r`  **Trigger** An enemy within a 10-foot emanation uses a manipulate action or a move action, makes a ranged attack, or leaves a square in the area during a move action it's using\n* * *\n\n**Effect** The clockwork infantry lashes out with their halberds. The triggering enemy takes 2d10+10 untyped damage (`DC 27 Reflex check` save). If the enemy critically fails this saving throw and the trigger was a manipulate action, the damage disrupts that action."

  - name: "Troop Defenses"
    desc: "  **HP** 195 (4 segments); **Thresholds** 130 (3 segments), 65 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Halberd Sweep"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The clockwork infantry engages in a coordinated melee attack against each enemy in a 10-foot emanation, with a `DC 27 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d10+2 untyped damage\n\n`pf2:2` 2d10+10 untyped damage\n\n`pf2:3` 3d10+12 untyped damage"

  - name: "Raise Defenses"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The clockwork soldiers of the infantry extend external plates on mechanical actuators to defend the troop or an adjacent creature. The creature gains a +2 circumstance bonus to AC until the start of the infantry's next turn, or until it is no longer adjacent to the infantry, whichever comes first."
 
```

```encounter-table
name: Clockwork Infantry
creatures:
  - 1: Clockwork Infantry
```



With each unit being 500 pounds of metal and magic, a clockwork infantry is a force to be reckoned with on the battlefield. Needing no food, shelter, or rest and feeling no pain, clockwork infantry can advance where living units have great trouble. With no morale that can be broken or minds that can be beguiled, they patrol without stopping and show no mercy. The only drawback is the need to wind them more often than simpler clockwork mechanics.
