---
title: "Xulgath Dinosaur Cavalry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.MvWzD22qi92ZF6q0" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Xulgath Dinosaur Cavalry"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Xulgath Dinosaur Cavalry"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[dinosaur]]
trait_03: [[humanoid]]
trait_04: [[troop]]
trait_05: [[xulgath]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Intimidation: +24, Dinosaur Lore: +24"
abilityMods: [8, 2, 5, -1, 4, 3]
speed: 30 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +29, __Ref__ +20, __Will__ +23"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, (4 segments); Thresholds 160 (3 segments), 80 (2 segments); __Weaknesses__ area damage 15, splash damage 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Javelin Barrage"
    desc: "`pf2:2`  The xulgaths draw javelins and launch a coordinated barrage at range. This barrage is a 10-foot burst within 30 feet that deals 4d8 piercing damage (`DC 30 Reflex check` save). When the cavalry is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet `DC 33 Fortitude check`\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

  - name: "Troop Defenses"
    desc: "  **HP** 240 (4 segments); **Thresholds** 160 (3 segments), 80 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Mounted Troop"
    desc: "  Effects that target only animals or only humanoids may not work on the valkyrie tempest, subject to the GM's discretion."

  - name: "Spears, Teeth, and Horns"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The cavalry makes a coordinated melee attack against each enemy in 10-foot emanation, with a `DC 30 Reflex check` save. The damage dealt depends on the number of actions.\n\n`pf2:1` 2d6+2 piercing damage\n\n`pf2:2` 4d6+10 piercing damage\n\n`pf2:3` 5d6+15 piercing damage"

  - name: "Trample"
    desc: "`pf2:3`  [Size], [Listed Strike], `Reflex check`\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Xulgath Dinosaur Cavalry
creatures:
  - 1: Xulgath Dinosaur Cavalry
```



Xulgaths have been breeding and training dinosaurs for millennia, and the bonds between them are as familiar and strong as that between any other humanoid and their domesticated companion of choice. While most of the creatures are used primarily as beasts of burden, elite xulgath soldiers known as roughriders train the most vicious and aggressive dinosaurs from numerous species to serve as vicious and terrifying mounts, capable of punching through defensive lines and smashing fortifications to splinters as easily as they scatter enemy soldiers.
