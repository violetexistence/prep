---
title: "Qadiran Camel Corps"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.egHaHp1lqQBZdKdR" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Qadiran Camel Corps"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Qadiran Camel Corps"
level: "Creature 6"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[troop]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Common, Kelish"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Diplomacy: +11, Nature: +13, Survival: +13"
abilityMods: [5, 3, 2, 0, 1, 2]
speed: 35 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +14, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, (4 segments); Thresholds 60 (3 segments), 30 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

  - name: "Desert-Adapted Troop"
    desc: "  A camel corps is well-adapted to heat and deserts. They treat environmental heat as if it was one step less severe, and if the camel mounts have eaten and drank their fill, the corps can Subsist for 1 week without needing to attempt Survival checks."

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 90 (4 segments); **Thresholds** 60 (3 segments), 30 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Dust Storm"
    desc: "`pf2:1`  **Requirements** The camel corps is in a desert or similar region\n* * *\n\n**Effect** The camel corps Steps, whipping up sand into a short-lived storm that obscures the surrounding region. Until the end of their next turn, the camel corps is [[Conditions/Concealed|Concealed]] from all creatures more than 15 feet away, and all creatures more than 15 feet away are concealed to the camel corps."

  - name: "Mounted Troop"
    desc: "  Effects that target only animals or only humanoids may not work on the valkyrie tempest, subject to the GM's discretion."

  - name: "Reflective Arrows"
    desc: "`pf2:2`  Adjusting to the angle of the sun, the camel riders draw their shortbows, then launch a ranged attack in the form of an arcing volley. This volley is a 10-foot burst within 60 feet that deals 3d6 piercing damage (`DC 21 Reflex check` save). In areas of bright light, such as outside during the day, the targets take a –1 circumstance penalty to the save. When the camel corps is reduced to 2 segments, this area decreases to a 5-foot burst.\n\n[[Bestiary Effects/Effect_ Reflective Arrows (Penalty)|Effect: Reflective Arrows (Penalty)]]"

  - name: "Scimitar Assault"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The camel corps engages in a coordinated melee attack against each enemy in a 5-foot emanation (`DC 21 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6+1 slashing damage\n\n`pf2:2` 2d6+7 slashing damage\n\n`pf2:3` 2d6+11 slashing damage"

  - name: "Trailblazing Stride"
    desc: "  While moving on land, the Qadiran camel corps ignores the effects of non-magical difficult terrain."
 
```

```encounter-table
name: Qadiran Camel Corps
creatures:
  - 1: Qadiran Camel Corps
```



Navigating the deserts of Golarion requires trained individuals and often specialized mounts to keep them safe. The Qadiran camel corps are one such example of those who embark on long patrols, hunt down brigands, and dispatch any natural threats that might trouble travelers.
