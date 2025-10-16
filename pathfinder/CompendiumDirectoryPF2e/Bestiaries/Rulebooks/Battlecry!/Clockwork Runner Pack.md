---
title: "Clockwork Runner Pack"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.BYh3tkAX9SgGFuXD" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Clockwork Runner Pack"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Clockwork Runner Pack"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
trait_04: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12, Stealth: +13"
abilityMods: [2, 6, 0, -5, 5, -5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +15, __Will__ +9"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, (4 segments); Thresholds 50 (3 segments), 25 (2 segments); __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ area damage 5, electricity 5, splash damage 5, orichalcum 5"
abilities_top:
  - name: ""

  - name: "Wind-Up"
    desc: "  48 hours, [[Actions/disable-device dc=19|disable-device dc=19]], standy\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 75 (4 segments); **Thresholds** 50 (3 segments), 25 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Fire Crossbows"
    desc: "`pf2:2`  The clockwork runners reload the crossbows built onto their backs, then launch a ranged attack in the form of a volley. This volley is a 10-foot burst within 120 feet that deals 2d8 piercing damage (`DC 19 Reflex check` save). When the clockwork runners are reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Scratch and Bite"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The clockwork runners engage in a pack attack against each enemy in a 5-foot emanation, with a `DC 19 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8 untyped damage\n\n`pf2:2` 2d8+3 untyped damage\n\n`pf2:3` 2d8+7 untyped damage"

  - name: "War Pounce"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The clockwork runner pack Strides, ignoring difficult terrain (but not greater difficult terrain). At the end of this movement, each enemy in a 5-foot emanation takes 1d8 untyped damage (`DC 19 Reflex check` save)."
 
```

```encounter-table
name: Clockwork Runner Pack
creatures:
  - 1: Clockwork Runner Pack
```



Clockwork runners are units build for speed. Mimicking large cats, they sacrifice sturdiness for agility. Runners provide excellent battlefield control by speedily traversing diverse terrain types, able to cut off enemy units and provide covering fire for allies with their built-in crossbows. As clockworks, they do need to be rewound, making them less ideal for longer deployments.
