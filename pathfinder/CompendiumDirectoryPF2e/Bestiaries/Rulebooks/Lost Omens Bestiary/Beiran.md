---
title: "Beiran"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.lost-omens-bestiary.Actor.5arJo93OwqfLB3AY" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/fey
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Beiran"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens Shining Kingdoms"
name: "Beiran"
level: "Creature 3"

alignment: ""
size: "grg"
trait_01: [[cold]]
trait_02: [[fey]]
trait_03: [[troop]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Deception: +8, Diplomacy: +8, Stealth: +10"
abilityMods: [1, 4, 0, 1, 1, 3]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder Lost Omens Shining Kingdoms_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +12, __Will__ +9"
hp: 54
health:
  - name: ""
  - name: HP
    desc: "54, (4 segments); Thresholds 36 (3 segments), 18 (2 segments); __Immunities__  cold; __Weaknesses__ cold 5, area damage 5, cold iron 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  Troops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

  - name: "Unseasonable Cold"
    desc: " (aura,cold,primal) Wherever the frosthunt goes, winter follows. The temperature within a quarter mile of a frosthunt drops to mild cold, then to severe cold within 500 feet, and extreme cold within 50 feet."

attacks:
  - name: ""

  - name: "Primal Innate Spells"
    desc: "DC 17, attack +0; __2nd __  _[[Spells/Chilling Spray|Chilling Spray (x3)]]_\n__Cantrips__  __(2nd)__ _[[Spells/Frostbite|Frostbite]]_"

  - name: "Icy Japes"
    desc: "`pf2:1` (cold) **Frequency** once per round\n* * *\n\n**Effect** The beirans descend on their prey, biting and clawing at each enemy in a 5-foot emanation, with a `DC 17 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d6 slashing damage plus 1 cold damage\n\n`pf2:2` 2d6+2 slashing damage plus 1d4 cold damage\n\n`pf2:3` 2d6+5 cold damage plus 1d4 cold damage"
 
```

```encounter-table
name: Beiran
creatures:
  - 1: Beiran
```



With pale-blue skin and white hair, the wicked beiran fey are among the most unrepentantly cruel of the First World's spawn. Commonly called ice fey, these wintry tricksters are sadistic and without remorse in their desire to spread the cold wherever they go. Beirans find freezing temperatures to be the most comfortable; the fact that other creatures suffer under such conditions is part of the fun. While a single beiran is unlikely to change the temperature of a given space by more than a few degrees, they're highly social creatures, and it's uncommon to find fewer than a few dozen beirans at any one time.

Though beirans are unapologetic in their rude nature, there's one type of creature they'll bow to and take orders from with no questions asked: winter hags. For reasons unknown, beirans are particularly subservient to these hags and will often flock to one in large numbers. Under a winter hag, the fey will make a bad cold snap worse for a suffering town. Fires will be extinguished, wood ruined, food stolen, all of which suit the mysterious tastes of the winter hag and her preference for joyless landscapes. What the beirans receive from this relationship is uncertain, though some fey academics believe it's possible that the first beirans were created by winter hags, much in the same way that the green men created leshies.

While beirans are most common in northern lands such as Irrisen and the Land of the Linnorm Kings, they also have a surprising presence in the Shining Kingdoms. When Queen Elvanna of Irrisen opened up portals to the Eternal Winter of Irrisen, several of them arrived in the town of Heldren in Taldor, and even today, some still haunt the woods around it. Eighteen years ago in Falcon's Hollow, a particularly nasty batch of beirans were involved in the Carnival of Tears, an icy circus that left many townsfolk dead in its wake before adventurers dismantled it. Winters in Kyonin are often heralded by swarms of fiend-touched beirans flooding in from the Tanglebriar, leaving the Wylderhearts on fey duty for months at a time.
