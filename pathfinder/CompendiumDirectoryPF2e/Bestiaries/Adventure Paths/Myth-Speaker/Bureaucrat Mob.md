---
title: "Bureaucrat Mob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.myth-speaker-bestiary.Actor.sPy2VUgObOcUKceK" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Bureaucrat Mob"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #216: The Acropolis Pyre"
name: "Bureaucrat Mob"
level: "Creature 4"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common, Iblydan"
skills:
  - name: "Skills"
    desc: "Intimidation: +9, Performance: +12, Society: +11"
abilityMods: [3, 2, 1, 3, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder #216: The Acropolis Pyre_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +9, __Ref__ +8, __Will__ +12"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45, (4 segments); Thresholds 30 (3 segments), 15 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Aura of Argumentation"
    desc: " (auditory,aura,mental) 30 feet. The mob argues among itself even while attacking; creatures within the aura must succeed at a `DC 18 Will check` save or be [[Conditions/Confused|Confused]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "[[Bestiary Ability Glossary/Troop Movement|Troop Movement]]"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Knives Drawn"
    desc: "`pf2:1`  `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The mob descends on its opponents with knives, dealing damage to each enemy in its space and in a 5-foot emanation, with a `DC 18 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 2d4 piercing damage\n\n`pf2:2` 2d4+5 piercing damage\n\n`pf2:3` 2d4+7 piercing damage"

  - name: "Orate"
    desc: "`pf2:1` (auditory) The mob shouts at its opponents, dealing 2d6 sonic damage to any creature within 30 feet that can hear it (`DC 18 Fortitude check` save)."
 
```

```encounter-table
name: Bureaucrat Mob
creatures:
  - 1: Bureaucrat Mob
```




