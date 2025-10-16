---
title: "Dancing Night Parade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.fists-of-the-ruby-phoenix-bestiary.Actor.vf59nmtYaF0se9Ui" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/spirit
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Dancing Night Parade"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Dancing Night Parade"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[spirit]]
trait_03: [[troop]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +33, Deception: +37, Performance: +37, Society: +32, Dancing Lore: +32"
abilityMods: [8, 7, 5, 5, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, __Will__ +34"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450, Thresholds 300 (3 segments), 150 (2 segments); __Weaknesses__ bludgeoning 15, area damage 20, splash damage 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "Riotous Parade"
    desc: "  60 feet. The night parade sweeps up those nearby in a riotous celebration. All creatures in the aura must attempt a `DC 39 Will check` save. The target is then temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The target is unafflicted.\n\n**Success** The target laughs and dances. It can't use reactions as long as it stays in the area, and if it attempts to use a concentrate action, it must succeed at a `DC 5 Flat check` check; on a failure, the action is lost.\n\n**Failure** As success, except the target is also [[Conditions/Slowed|Slowed 1]] while in the area.\n\n**Critical Failure** As success, except the target is also slowed 1 while in the area and the flat check DC is 10."

  - name: "Troop Movement"
    desc: "  Whenever a troop Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square enters difficult terrain, the extra movement cost applies to the whole troop."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Compendium.pf2e.bestiary-ability-glossary-srd.Item.RJbI07QSiYp0SF9A|Troop Defenses]]"
    desc: "  **Thresholds** 300 (3 segments), 150 (2 segments)\n* * *\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

attacks:
  - name: ""

  - name: "Seiya! Soiya!"
    desc: "`pf2:2` (emotion,mental,sonic) The night parade shouts a series of energetic call-and-responses, dealing 3d10 sonic damage and 4d6 mental damage to all creatures in a 10-foot burst within 20 feet (`DC 41 Will check` save). If the troop is reduced to 8 or fewer squares, this area decreases to a 5-foot burst."

  - name: "Wasshoi! Wasshoi!"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The night parade dances with wild abandon, unintentionally striking nearby creatures. It deals damage to each adjacent creature (`DC 41 Reflex check` save), and any creature that fails its save is pushed 10 feet in any direction as the night parade bounces it overhead. The damage depends on the number of actions.\n\n`pf2:1` 1d10+7 bludgeoning damage\n\n`pf2:2` 4d10+14 bludgeoning damage\n\n`pf2:3` 6d10+14 bludgeoning damage"
 
```

```encounter-table
name: Dancing Night Parade
creatures:
  - 1: Dancing Night Parade
```




