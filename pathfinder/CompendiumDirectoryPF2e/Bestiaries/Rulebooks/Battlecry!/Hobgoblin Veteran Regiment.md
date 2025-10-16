---
title: "Hobgoblin Veteran Regiment"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.Td5jgGuZvNBVQngE" 
tags:
  - pf2e/creature/type/hobgoblin
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Hobgoblin Veteran Regiment"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Hobgoblin Veteran Regiment"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[hobgoblin]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Intimidation: +18"
abilityMods: [6, 3, 4, 0, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +15, __Will__ +19"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (4 segments); Thresholds 100 (3 segments), 50 (2 segments); __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hobgoblin Phalanx"
    desc: "`pf2:1`  Many of the hobgoblins raise their shields to protect their allies. The regiment gains a +2 circumstance bonus to AC until the start of their next turn."

  - name: "Troop Defenses"
    desc: "  **HP** 150 (4 segments); **Thresholds** 100 (3 segments), 50 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

  - name: "Watchful"
    desc: "  The hobgoblin regiment is trained to guard from all sides with shields at the ready. The hobgoblin regiment can't be made [[Conditions/Off-Guard|Off-Guard]] by flanking creatures of the troop's level or lower."

attacks:
  - name: ""

  - name: "Disciplined Strikes"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The hobgoblins engage in a coordinated melee attack against each enemy in a 5-foot emanation, with a `DC 25 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 slashing damage\n\n`pf2:2` 2d8+9 slashing damage\n\n`pf2:3` 3d8+11 slashing damage"

  - name: "Overrun"
    desc: "`pf2:3`  The hobgoblin veteran regiment marches inexorably forward, crushing enemies in their path. The regiment Strides up to double its Speed and can move through the spaces of Large or smaller creatures, dealing 2d8+9 slashing damage (`DC 25 Reflex check` save) to each creature whose space it enters. The regiment can attempt to Overrun the same creature only once in a single use of Overrun. When the regiment is reduced to 2 segments, the damage decreases to 1d8+2 slashing damage."

  - name: "Shortbow Volley"
    desc: "`pf2:2`  The hobgoblins draw their shortbows, then launch a ranged attack in the form of a volley. This volley is a 10-foot burst within 60 feet that deals 4d6 piercing damage with a `DC 25 Reflex check` save. When the regiment is reduced to 2 segments, this area decreases to a 5-foot burst."
 
```

```encounter-table
name: Hobgoblin Veteran Regiment
creatures:
  - 1: Hobgoblin Veteran Regiment
```



There are few sights as intimidating as a regiment of well-armed hobgoblin soldiers advancing across a battlefield. Exceptionally capable of defending themselves and tenacious to a fault, such hobgoblins are used as a precision tool, exploiting the enemy's weakest point and tearing it wide open to collapse entire defensive lines.
