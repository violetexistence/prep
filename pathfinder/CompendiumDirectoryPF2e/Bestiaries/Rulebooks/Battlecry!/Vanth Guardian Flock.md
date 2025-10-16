---
title: "Vanth Guardian Flock"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.3om22P58nZSuqNrv" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Vanth Guardian Flock"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Vanth Guardian Flock"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
trait_03: [[troop]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Lifesense (Imprecise) 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +27, Intimidation: +24, Occultism: +22, Religion: +22, Stealth: +27, Boneyard Lore: +24"
abilityMods: [8, 5, 3, 3, 4, 3]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +21, __Will__ +25"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, (4 segments); Thresholds 160 (3 segments), 80 (2 segments); __Immunities__  death effects,  disease; __Weaknesses__ area damage 12, splash damage 12; __Resistances__ poison 15, void 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Frightful Presence"
    desc: " (aura,emotion,fear,mental) 20 feet `DC 30 Will check`\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Reactive Relocation"
    desc: "`pf2:r` (teleportation) **Trigger** A creature hits the guardian flock with an attack roll\n* * *\n\n**Effect** After the attack roll is resolved, the troop pools dimensional magic to rapidly change their position. They cast 4th-rank [[Spells/Translocate|Translocate]], except their range is limited to 40 feet."

  - name: "Troop Defenses"
    desc: "  **HP** 240 (4 segments); **Thresholds** 160 (3 segments), 80 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 33, attack +26; __6th __  _[[Spells/Holy Light|Holy Light (x3)]]_; __5th __  _[[Spells/Locate|Locate (x3)]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (at will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (at will, self only)]]_"

  - name: "Guardians' Curse"
    desc: "`pf2:2` (curse,divine,misfortune) **Frequency** three times per day\n* * *\n\n**Effect** The guardian flock bestows a curse upon all enemies in a 5-foot emanation by touching them with their scythes. Each affected creature must attempt a `DC 33 Will check` save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to Guardians' Curse for 24 hours.\n\n**Success** The target feels a momentary shudder of doom and is [[Conditions/Stupefied|Stupefied 1]] for 1 minute by the distracting sensation.\n\n**Failure** The target becomes morose and glum as it accepts its own inevitable fate. For 1 hour, the target is [[Conditions/Stupefied|Stupefied 2]]. Each time the target gains the dying condition, the stupefied condition value increases by 1, to a maximum value of [[Conditions/Stupefied|Stupefied 4]].\n\n**Critical Failure** As failure, but the effect is permanent."

  - name: "Harvest the Wicked"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The vanths swing their scythes in a coordinated melee attack. Each enemy in a 5-foot emanation must attempt a `DC 30 Reflex check` save. The damage depends on the number of actions. The slashing damage is treated as adamantine, cold iron, and silver.\n\n`pf2:1` 1d10+1 slashing damage plus 1d6 shepherd's touch\n\n`pf2:2` 2d10+3 slashing damage plus 3d6 shepherd's touch\n\n`pf2:3` 2d10+7 slashing damage plus 4d6 shepherd's touch"

  - name: "Shepherd’s Touch"
    desc: "  The physical damage dealt by the guardian flock's Harvest the Wicked ability is treated as coming from a weapon with a ghost touch property rune. In addition, the vanths deal the listed damage as void damage to living creatures or vitality damage to undead."
 
```

```encounter-table
name: Vanth Guardian Flock
creatures:
  - 1: Vanth Guardian Flock
```



Vanth psychopomps are eternal guardians of the cycle of life and death. When souls are threatened by fiends or other malevolent forces, they gather together to cut the threat down.
