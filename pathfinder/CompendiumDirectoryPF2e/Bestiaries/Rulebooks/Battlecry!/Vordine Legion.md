---
title: "Vordine Legion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.rdS6HBEtST3WKnSA" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/troop
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Vordine Legion"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Vordine Legion"
level: "Creature 10"

alignment: ""
size: "grg"
trait_01: [[devil]]
trait_02: [[fiend]]
trait_03: [[troop]]
trait_04: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Greater Darkvision"
languages: "Common, Diabolic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +24, Intimidation: +22, Religion: +19, Warfare Lore: +22"
abilityMods: [5, 5, 7, 2, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +22, __Ref__ +19, __Will__ +16"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, (4 segments); Thresholds 120 (3 segments), 60 (2 segments); __Weaknesses__ area damage 10, splash damage 10; __Resistances__ physical 10 (except silver), poison 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Reactive Attack"
    desc: "`pf2:r`  **Trigger** A creature within the vordine legion's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The creature takes 2d8+11 piercing damage (`DC 26 Reflex check` save); this damage has the magical and unholy traits. If the creature critically fails its saving throw and the trigger was a manipulate action, the legion disrupts that action."

  - name: "Troop Defenses"
    desc: "  **HP** 180 (4 segments); **Thresholds** 120 (3 segments), 60 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +0; __4th __  _[[Spells/Translocate|Translocate (at will)]]_"

  - name: "Burning March"
    desc: "`pf2:2` (divine,fire,unholy) The vordine legion Strides, leaving an orderly pattern of burning hoofprints in each square they enter. The hoofprints continue to burn for 1 minute. Any creature on the ground that begins its turn in, or enters a square with, burning hoofprints takes 2d8 fire damage."

  - name: "Impaling Barrage"
    desc: "`pf2:2` (magical,unholy) The vordine legion releases a hail of tridents. This hail is a 10-foot burst within 40 feet that deals 4d8 piercing damage (`DC 26 Reflex check` save). Creatures that fail the saving throw are [[Conditions/Clumsy|Clumsy 1]] until the start of the vordine legion's next turn ([[Conditions/Clumsy|Clumsy 2]] on a critical failure). When the vordines are reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Tines of Dis"
    desc: "`pf2:1` (magical,unholy) **Frequency** once per round\n* * *\n\n**Effect** The vordines of the legion make coordinated melee attacks with their tridents. Each enemy within a 5-foot emanation must attempt a `DC 26 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 piercing damage\n\n`pf2:2` 2d8+11 piercing damage\n\n`pf2:3` 3d8+14 piercing damage"
 
```

```encounter-table
name: Vordine Legion
creatures:
  - 1: Vordine Legion
```



Vordines are the foot soldiers of Hell, dispatched in vast armies from the iron city of Dis to guard Hell's uppermost layers and crush the enemies of the archdevils who rule there. Indefatigable and pitiless, a legion of vordines strikes with a ruthless precision that commands fear and envy throughout the multiverse in equal measure. Although they usually serve at the command of more powerful devils, such as the tyrannical nessari, every legion also observes a unique internal hierarchy that enables another vordine to assume command at a moment's notice should it become necessary.
