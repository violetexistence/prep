---
title: "Mitflit Vermin Cavalry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.4Bvb7rVBB5gg7a2N" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/fey
  - pf2e/creature/type/gremlin
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Mitflit Vermin Cavalry"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Mitflit Vermin Cavalry"
level: "Creature 4"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[fey]]
trait_03: [[gremlin]]
trait_04: [[troop]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Diplomacy: +8, Nature: +10, Stealth: +12"
abilityMods: [0, 5, 1, -1, 2, -1]
speed: 15 feet,  climb 15 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, (4 segments), Thresholds 40 (3 segments), 20 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 60 (4 segments), **Thresholds** 40 (3 segments), 20 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Primal Innate Spells"
    desc: "DC 0, attack +0; __2nd __  _[[Spells/Speak with Animals|Speak with Animals]]_; __1st __  _[[Spells/Vanishing Tracks|Vanishing Tracks]]_\n__Cantrips__  __(2nd)__ _[[Spells/Prestidigitation|Prestidigitation]]_"

  - name: "Crawling Stabs"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The mitflits thrust with their shortswords, coordinated with bites from their giant vermin mounts. All enemies in a 5-foot emanation must attempt a `DC 18 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d6 piercing damage\n\n`pf2:2` 2d6+4 piercing damage\n\n`pf2:3` 2d6+8 piercing damage"

  - name: "Leaping Charge"
    desc: "`pf2:2`  The mitflit vermin cavalry Leaps up to 30 feet. If it moves at least 15 feet, the cavalry deals 2d6+4 piercing damage (`DC 18 Reflex check` save) to each enemy within a 5-foot emanation at the end of its movement."

  - name: "Mounted Troop"
    desc: "  Effects that target only animals or only humanoids may not work on the mitflit vermin cavalry, subject to the GM's discretion."

  - name: "Vengeful Wrath"
    desc: " (emotion,mental) As long as it's not frightened, the mitflit vermin cavalry gains a +2 status bonus to the DC of its Crawling Stabs ability against creatures that have previously damaged or tormented it."
 
```

```encounter-table
name: Mitflit Vermin Cavalry
creatures:
  - 1: Mitflit Vermin Cavalry
```



Though mitflits are known as cowardly gremlins, they can be urged into an aggressive fervor by the right leader. Mounted on giant ticks, centipedes, and other verminous arthropods, these mitflits overcome their self-loathing to take the fight to their enemies.
