---
title: "Dromaar Company"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.R1Ukw41ygDmnAmJk" 
tags:
  - pf2e/creature/type/dromaar
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Dromaar Company"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Dromaar Company"
level: "Creature 6"

alignment: ""
size: "grg"
trait_01: [[dromaar]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[orc]]
trait_05: [[troop]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +15, Intimidation: +11, Survival: +11"
abilityMods: [5, 4, 2, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +17, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, 4 segments); Thresholds 60 (3 segments), 30 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 90 (4 segments); **Thresholds** 60 (3 segments), 30 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Bola Hurl"
    desc: "`pf2:1`  The dromaars draw bolas and toss them in a 15-foot cone. Each creature in this area takes 3d6 nonlethal bludgeoning damage (`DC 21 Reflex check` save). A creature who fails this saving throw is also knocked [[Conditions/Prone|Prone]]."

  - name: "Charge the Fallen"
    desc: "`pf2:2`  The dromaar company Strides up to twice, sweeping with their axes. They deal 2d8+5 slashing damage (`DC 21 Reflex check` save) to each enemy in a 5-foot emanation at the end of their movement. This damage increases by 5 if the target is [[Conditions/Prone|Prone]]."

  - name: "Disciplined Strikes"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The dromaars coordinate melee attacks with their axes against all enemies in a 5-foot emanation (`DC 21 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d8 slashing damage\n\n`pf2:2` 2d8+5 slashing damage\n\n`pf2:3` 2d8+10 slashing damage"
 
```

```encounter-table
name: Dromaar Company
creatures:
  - 1: Dromaar Company
```



Numerous dromaar mercenary companies operate in and around Belkzen, providing their strength at arms to any hold that requests their services. These disciplined warriors march confidently into battle, bringing their axes to bear against all who stand in their way.
