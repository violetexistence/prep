---
title: "Halfling Lucky Draw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.K6PtvumX6CbtYaQg" 
tags:
  - pf2e/creature/type/halfling
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Halfling Lucky Draw"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Halfling Lucky Draw"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[halfling]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common, Halfling"
skills:
  - name: "Skills"
    desc: "Deception: +18, Diplomacy: +16, Occultism: +16, Performance: +18, Stealth: +16"
abilityMods: [0, 4, 1, 3, 1, 6]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +16, __Will__ +19"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, (4 segments); Thresholds 90 (3 segments), 45 (2 segments); __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 135 (4 segments); **Thresholds** 90 (3 segments), 45 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Occult Spontaneous Spells"
    desc: "DC 23, attack +20; __4th __ (2 slots) _[[Spells/Confusion|Confusion]]_, _[[Spells/Force Barrage|Force Barrage]]_; __3rd __ (3 slots) _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Bad Deal"
    desc: "`pf2:2` (auditory,emotion,linguistic,mental,misfortune,occult) The halflings mock and taunt their enemies with quick Harrow readings that predict doom. The troop chooses a number of creatures equal to the number of its remaining segments within 60 feet. Each target must attempt a `DC 23 Will check` save. On a failure, the target must roll their next attack roll, saving throw, or skill check twice and use the worse result.\n\n[[Bestiary Effects/Effect_ Bad Deal|Effect: Bad Deal]]"

  - name: "False Cuts"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The halflings feint with their cards and then lash out with their daggers in a coordinated melee attack against enemies in a 5-foot emanation, with a `DC 23 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d4 piercing + 1d4 precision precision damage\n\n`pf2:2` 2d4+7 piercing + 2d4 precision precision damage\n\n`pf2:3` 3d4+10 piercing + 2d4 precision precision damage"

  - name: "Troop Harrowing"
    desc: " (mental,occult) When the halfling lucky draw Casts a Spell that targets a single creature, some of the constituent members can perform a focused Harrow reading on the target as part of Casting the Spell. The lucky draw attempts an `Occultism check` skill check against the target's Will DC. On a success, the target takes a –1 status penalty to their saving throw or AC against the spell (–2 on a critical success). If the lucky draw critically fails this check, their reading portends bad news for the halflings and they become [[Conditions/Frightened|Frightened 2]].\n\n[[Bestiary Effects/Effect_ Troop Harrowing|Effect: Troop Harrowing]]"
 
```

```encounter-table
name: Halfling Lucky Draw
creatures:
  - 1: Halfling Lucky Draw
```




