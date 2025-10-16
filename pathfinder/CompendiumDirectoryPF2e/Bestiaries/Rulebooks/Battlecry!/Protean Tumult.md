---
title: "Protean Tumult"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.byWkcSBvfm4n7I3m" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Protean Tumult"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Protean Tumult"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[monitor]]
trait_02: [[protean]]
trait_03: [[troop]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Chthonian, Protean, Empyrean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +22, Intimidation: +22, Survival: +20"
abilityMods: [4, 6, 4, 0, 2, 4]
speed: 25 feet,  fly 30 feet,  swim 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +22, __Ref__ +25, __Will__ +19"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, (4 segments); Thresholds 140 (3 segments), 70 (2 segments); __Weaknesses__ area damage 10, splash damage 10; __Resistances__ precision 8"
abilities_top:
  - name: ""

  - name: "Entropy Sense"
    desc: " (divine,prediction) A protean tumult can anticipate the most likely presence of a creature through a supernatural insight into chaotic probabilities and chance. This grants it the ability to sense creatures within the listed range. Veil of privacy prevents a creature from being detected via entropy sense automatically (without a counteract check)."

abilities_mid:
  - name: ""
  - name: "Fast Healing"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Protean Anatomy"
    desc: " (divine) A protean's vital organs shift and change shape and position constantly. Immediately after the protean takes acid, electricity, or sonic damage, it gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first. The protean is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the protean automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones.\n\n[[Bestiary Effects/Effect_ Protean Anatomy|Effect: Protean Anatomy]]"

  - name: "Troop Defenses"
    desc: "  **HP** 210 (4 segments); **Thresholds** 140 (3 segments), 70 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +0\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "Chaos Flux"
    desc: "  A protean tumult is less organized and more vicious than most troops. It can move into other creatures' spaces, and other creatures can move into its spaces. Its spaces are difficult terrain to non-protean creatures. A creature that willingly moves into a protean tumult's space takes 1d12+1 bludgeoning damage (`DC 29 Reflex check` save); a creature takes this damage only once per round."

  - name: "Chaos Strike"
    desc: " (divine,morph) **Frequency** once per round\n* * *\n\n**Effect** The protean tumult chooses adamantine, cold iron, or silver; the damage dealt by its Claws, Jaws, and Tails is treated as that material for 1 minute or until it uses Chaos Strike again."

  - name: "Claws, Jaws, and Tails"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The tumult viciously attacks each enemy within a 5-foot emanation (`DC 29 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d12+1 bludgeoning damage\n\n`pf2:2` 2d12+10 bludgeoning damage\n\n`pf2:3` 3d12+11 bludgeoning damage"

  - name: "Stupefying Swipe"
    desc: "`pf2:2` (divine,emotion,mental) The protean tumult makes their way across the battlefield. It Strides. At the end of this movement, they lash out at the enemy with tentacles and other blunt body parts, dealing 2d12+10 bludgeoning damage in a 5-foot emanation (`DC 29 Reflex check` save). A creature who fails this save is also [[Conditions/Stupefied|Stupefied 2]] for 2 rounds ([[Conditions/Stupefied|Stupefied 3]] on a critical failure)."
 
```

```encounter-table
name: Protean Tumult
creatures:
  - 1: Protean Tumult
```



Due to the inherently chaotic nature of proteans, many would assume they are incapable of cooperation. However, they are cunning enough to be able to unite in the face of danger or at the behest of more powerful beings, sometimes acting as a group called a protean tumult. Such an association is comprising of dozens of proteans of different shapes and sizes, many of whom continually alter their forms from moment to moment.
