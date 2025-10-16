---
title: "Ofalth Stampede"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.AHV0FTrbuPljLndw" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Ofalth Stampede"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Ofalth Stampede"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[troop]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Stealth: +28"
abilityMods: [7, 5, 6, 0, 2, 0]
speed: 30 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +24, __Will__ +25"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, (4 segments), filth wallow; Thresholds 180 (3 segments), 90 (2 segments); __Immunities__  disease,  poison; __Weaknesses__ area damage 15, splash damage 15"
abilities_top:
  - name: ""

  - name: "Refuse Pile"
    desc: "  When an ofalth stampede is not in danger, they can spend 1 minute settling into a 20-foot pile that looks like a heap of garbage. Until the next time they take an action, the troop gains a +2 circumstance bonus to AC. A creature that enters the area of the garbage heap or interacts with it must attempt a save against the ofalth stampede's stench."

abilities_mid:
  - name: ""
  - name: "Filth Wallow"
    desc: "  A trash stampede gains fast healing 10 when in an area with a high concentration of debris or excrement, such as a refuse heap or sewer."

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet `DC 33 Fortitude check`\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

  - name: "Troop Defenses"
    desc: "  **HP** 270 (4 segments), filth wallow; **Thresholds** 180 (3 segments), 90 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Offal Rain"
    desc: "`pf2:2`  The ofalth stampede hurls a tremendous amount of rotting trash, which rains down in a 10-foot burst within 60 feet. All creatures in the area take 4d10 bludgeoning damage (`DC 33 Reflex check` save). Creatures that fail the saving throw are also exposed to wretched weeps. When the troop is reduced to 2 segments, the area decreases to a 5-foot burst."

  - name: "Putrid Pummeling"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The ofalths pummel all enemies in a 10-foot emanation, with a `DC 33 Reflex check` save. The damage depends on the number of actions. Creatures that fail the saving throw are exposed to wretched weeps.\n\n`pf2:1` 1d12+3 bludgeoning damage\n\n`pf2:2` 3d12+7 bludgeoning damage\n\n`pf2:3` 4d12+10 bludgeoning damage"

  - name: "Wretched Weeps"
    desc: " (disease) **Saving Throw** `DC 36 Fortitude check`\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d4 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** 2d6 persistent bleed every hour and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"
 
```

```encounter-table
name: Ofalth Stampede
creatures:
  - 1: Ofalth Stampede
```



If a large city's waste management system spirals out of control, ofalths can grow and propagate unchecked. These reeking creatures haul tons of trash on their backs and carry a particularly virulent disease.
