---
title: "Apprentice Magician Clique"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.tKPZ1iDZukJDvzAK" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Apprentice Magician Clique"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Apprentice Magician Clique"
level: "Creature 5"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common, Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Arcana: +13, Deception: +10, Diplomacy: +10, Thievery: +12"
abilityMods: [0, 4, 1, 5, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +12, __Will__ +15"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, (4 segments); 75 (4 segments); Thresholds 50 (3 segments), 25 (2 segments); __Weaknesses__ area damage 4, splash damage 4"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 75 (4 segments); **Thresholds** 50 (3 segments), 25 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Arcane Prepared Spells"
    desc: "DC 22, attack +15; __3rd __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Wall of Wind|Wall of Wind]]_; __2nd __  _[[Spells/Blazing Bolt|Blazing Bolt]]_, _[[Spells/Entangling Flora|Entangling Flora]]_, _[[Spells/Laughing Fit|Laughing Fit]]_; __1st __  _[[Spells/Dizzying Colors|Dizzying Colors]]_, _[[Spells/Hydraulic Push|Hydraulic Push]]_, _[[Spells/Sleep|Sleep]]_\n__Cantrips__  __(3rd)__ _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Ignition|Ignition]]_, _[[Spells/Light|Light]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Barrage of Force"
    desc: "`pf2:2` (arcane,force) The apprentice magicians launch shards of pure magic at all creatures in a 10-foot burst within 120 feet. This barrage deals 5d4 force damage (`DC 19 Reflex check` save). When the clique is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Clique Spellcasting"
    desc: "  When the apprentice magician clique Casts a Spell, its members pool their arcane power into the spell. A creature who critically fails their save against the spell or whom the clique hits with a critical spell attack is also [[Conditions/Stupefied|Stupefied 1]] for 1 minute."

  - name: "Sparking Wands"
    desc: "`pf2:1` (arcane,electricity) **Frequency** once per round\n* * *\n\n**Effect** The apprentice magicians wave wands that shoot out minor bolts of electricity at short range. Each enemy in a 5-foot emanation must attempt a `DC 19 Reflex check` save. The damage dealt depends on the number of actions.\n\n`pf2:1` 1d8 electricity damage\n\n`pf2:2` 2d8+3 electricity damage\n\n`pf2:3` 2d8+7 electricity damage"
 
```

```encounter-table
name: Apprentice Magician Clique
creatures:
  - 1: Apprentice Magician Clique
```



Students at academies that teach magic sometimes form fast friendships. When not studying or blowing off steam together, these cliques might be called to defend their place of learning from outside attack.
