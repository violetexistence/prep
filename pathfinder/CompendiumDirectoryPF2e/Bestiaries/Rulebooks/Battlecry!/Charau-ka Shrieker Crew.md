---
title: "Charau-ka Shrieker Crew"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.9wgj9Jiej236yjBW" 
tags:
  - pf2e/creature/type/charau-ka
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Charau-ka Shrieker Crew"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Charau-ka Shrieker Crew"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[charau-ka]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic, Mwangi"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +16, Stealth: +14"
abilityMods: [4, 6, 3, 0, 3, 1]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +15, __Ref__ +19, __Will__ +15"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, 135 (4 segments); Thresholds 90 (3 segments), 45 (2 segments); __Weaknesses__ area damage 8, splash damage 8"
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

  - name: "Frenzied Hatchets"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The charau-ka engage in a coordinated melee attack against each enemy in a 5-foot emanation (`DC 23 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6+2 slashing damage\n\n`pf2:2` 2d6+10 slashing damage\n\n`pf2:3` 3d6+13 slashing damage"

  - name: "Shrieking Charge"
    desc: "`pf2:2` (auditory) With raucous shrieks, the shrieker crew charges forward. The troop Strides twice. If they move at least 10 feet, the crew deals 3d6+13 slashing damage (`DC 23 Reflex check` save) to each enemy in a 5-foot emanation at the end of the crew's movement. Each target who fails this save is also [[Conditions/Deafened|Deafened]] for 1 round."

  - name: "Storm of Daggers"
    desc: "`pf2:2`  The charau-ka hurl daggers as a ranged attack in the form of a barrage. This barrage is a 10-foot burst within 30 feet that deals 5d4 piercing damage (`DC 23 Reflex check` save). The range increases by 15 feet if the charau-ka are above their targets. When the shrieker crew is reduced to 2 segments, this area decreases to a 5-foot burst."
 
```

```encounter-table
name: Charau-ka Shrieker Crew
creatures:
  - 1: Charau-ka Shrieker Crew
```



Charau-ka are small humanoid apes who live in tropical jungles, especially within the Mwangi Expanse. Shrieker crews patrol the canopies close to charau-ka settlements, keeping predators at bay. Sometimes, a group of charau-ka will devote themselves to the demon lord Angazhan and become a bloodthirsty hunting party.
