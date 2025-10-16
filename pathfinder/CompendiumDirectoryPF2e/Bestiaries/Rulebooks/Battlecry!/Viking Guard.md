---
title: "Viking Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.8GzKWLw4LjZUoozH" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Viking Guard"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Viking Guard"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; "
languages: "Common, Skald"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +21"
abilityMods: [7, 3, 5, 1, 1, 1]
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
    desc: "195, Thresholds 130 (3 segments), 65 (2 segments); __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Sacrifice"
    desc: "`pf2:r`  **Requirements** The viking guard has a charge, and that creature is adjacent to the viking guard\n\n**Trigger** The viking guard's charge takes Hit Point damage\n* * *\n\n**Effect** The viking guard's charge takes half damage, and the viking guard takes the remainder of the damage."

  - name: "Troop Defenses"
    desc: "  **HP** 195 (4 segments); **Thresholds** 130 (3 segments), 65 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Berserker Strikes"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Battle axes in hand, the viking guard engages in a coordinated melee attack against enemies in a 5-foot emanation, with a `DC 27 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+3 slashing damage\n\n`pf2:2` 2d8+12 slashing damage\n\n`pf2:3` 3d8+15 slashing damage"

  - name: "Guard Charge"
    desc: "`pf2:1`  The viking guard designates an ally it can see to be its charge. The charge gains a +2 circumstance bonus to their AC, Reflex saves, and saves against fear when they are adjacent to the viking guard. Further, this allows the viking guard to use its Sacrifice and Shield Wall actions. A viking guard can have only one charge at a time, and if it designates a new charge, the old one loses all benefits. If the viking guard's charge is reduced to 0 Hit Points, the viking guard must succeed at a `DC 30 Will check` save or become [[Conditions/Frightened|Frightened 2]]; this is an emotion, fear, and mental effect.\n\n[[Bestiary Effects/Effect_ Guard Charge|Effect: Guard Charge]]"

  - name: "Shield Wall"
    desc: "  **Requirements** The viking guard has a charge, and that creature is adjacent to the viking guard\n* * *\n\n**Effect** Raising shields, the viking guard Strides up to twice its Speed as it protects its charge. The viking guard gains a +2 circumstance bonus to its AC against reactions triggered by this movement. The viking guard's charge can Stride the same distance as a reaction, moving with the troop to maintain the bonuses from Guard Charge during this movement."
 
```

```encounter-table
name: Viking Guard
creatures:
  - 1: Viking Guard
```



Battle-tested Ulfen barbarians, hunters, and warriors gather into an elite fighting unit who specialize in offering protection to their leaders in battle as well as protecting those who can afford their services. Traveling far and wide, single troops or entire companies can easily find work based on their reputations, from serving as bodyguards in small private armies to taking on specialized jobs.
