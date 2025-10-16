---
title: "Wight Battalion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.qSlw0pWIgYnRr58I" 
tags:
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Wight Battalion"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Wight Battalion"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[troop]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[wight]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +20, Intimidation: +18, Stealth: +18"
abilityMods: [6, 2, 4, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +15, __Will__ +18"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (4 segments); Thresholds 100 (3 segments), 50 (2 segments); __Weaknesses__ area damage 7, splash damage 7"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Final Grudge"
    desc: "`pf2:r`  **Trigger** The wight battalion is about to lose a segment due to Hit Point damage\n* * *\n\n**Effect** The wights strike out as they fall. Each enemy in a 5-foot emanation takes 2d4 piercing damage (`DC 25 Reflex check` save). This occurs before the battalion loses a segment."

  - name: "Fueled by Spite"
    desc: "  Each time a creature loses Hit Points due to the wight battalion's corrupting spite curse, the battalion gains 6 temporary Hit Points that last for 1 round.\n\n[[Bestiary Effects/Effect_ Fueled by Spite|Effect: Fueled by Spite]]"

  - name: "Troop Defenses"
    desc: "  **HP** 150 (4 segments); **Thresholds** 100 (3 segments), 50 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Corrupting Spite"
    desc: " (curse,divine,void) The wight battalion's attacks inflict a curse that makes a creature grow weak and spiteful. A living humanoid that dies while under this curse rises as a [[Monster Core/Wight|Wight]] after 1d4 rounds, controlled by the wight battalion that inflicted the curse. This new wight can't inflict corrupting spite and is [[Conditions/Clumsy|Clumsy 2]]. If the creating wight battalion dies or after roughly a month of existence, the new wight becomes autonomous and becomes a normal wight\n\n**Saving Throw** `DC 25 Fortitude check`\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] and doesn't treat any creatures as allies (1 round)\n\n**Stage 3** As stage 2, except [[Conditions/Drained|Drained 3]] (1 round)\n\n**Stage 4** As stage 2, except [[Conditions/Drained|Drained 4]] (1 round)."

  - name: "Hateful Daggers"
    desc: "`pf2:1`  The wights coordinate melee attacks with the daggers they were buried with. Each enemy within a 5-foot emanation attempts a `DC 25 Reflex check` save. The damage depends on the number of actions. On a failed save, the creature is also exposed to corrupting spite.\n\n`pf2:1` 2d4 piercing damage\n\n`pf2:2` 4d4+8 piercing damage\n\n`pf2:3` 4d4+14 piercing damage"
 
```

```encounter-table
name: Wight Battalion
creatures:
  - 1: Wight Battalion
```



Wights are malevolent undead, bent on desecrating the holy and determined to cause suffering to all living creatures. A lone wight is dangerous enough, but when compelled to act together, they are a force to be reckoned with. A wight battalion has the potential to curse entire armies, increasing their numbers until they become an unholy tide.
