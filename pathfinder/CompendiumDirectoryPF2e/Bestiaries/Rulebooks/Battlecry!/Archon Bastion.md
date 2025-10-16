---
title: "Archon Bastion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.JhyjcHNsKBATE127" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/holy
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Archon Bastion"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Archon Bastion"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[holy]]
trait_04: [[troop]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "Diabolic, Draconic, Empyrean, Utopian; Truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +32, Diplomacy: +28, Intimidation: +28, Religion: +28, Survival: +26"
abilityMods: [6, 2, 9, 3, 5, 5]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +30, __Ref__ +25, __Will__ +28"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, (4 segments); Thresholds 200 (3 segments), 100 (2 segments); __Immunities__  fear effects; __Weaknesses__ area damage 15, splash damage 15, unholy 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Archon's Aegis"
    desc: "`pf2:r`  **Trigger** An enemy damages an ally of the archon bastion and both are within 15 feet of the archon bastion\n* * *\n\n**Effect** The ally gains resistance 20 to all damage against the triggering damage and the enemy takes 1d8+4 piercing damage (`DC 34 Reflex check` save).\n\n[[Bestiary Effects/Effect_ Archon's Aegis|Effect: Archon's Aegis]]"

  - name: "Troop Defenses"
    desc: "  **HP** 300 (4 segments); **Thresholds** 200 (3 segments), 100 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __2nd __  _[[Spells/Share Life|Share Life (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Fearless Switch"
    desc: "`pf2:2` (teleportation) The archon bastion Strides so that at least one of its segments occupies the same space of a Large or smaller willing ally. That willing ally is then teleported to any open space it can fit into that is adjacent to any of the archon bastion's segments, using teleportation magic innate to the troop's individual shield archons. The archon bastion can move up to three allies in this fashion."

  - name: "Living Shields"
    desc: "`pf2:1`  The archon bastion grants each ally within a 5-foot emanation a +2 circumstance bonus to AC until that ally is no longer within the area or until the start of the archon bastion's next turn, whichever comes first. If the archon bastion uses Archon's Aegis against an attack against one of the shielded allies, the archon bastion gains the resistance and takes the damage rather than the ally.\n\n[[Bestiary Effects/Effect_ Living Shields|Effect: Living Shields]]"

  - name: "Smiting Lances"
    desc: "`pf2:1` (divine,holy) **Frequency** once per round\n* * *\n\n**Effect** The archon bastion engages in a uniform melee attack against each enemy in 10-foot emanation (`DC 34 Reflex check` save). The damage depends on the number of actions. An unholy creature that fails its save against this effect takes an additional 2d6 spirit damage (or 1d6 spirit damage for the one-action version).\n\n`pf2:1` 1d8+4 piercing damage\n\n`pf2:2` 3d8+14 piercing damage\n\n`pf2:3` 4d8+19 piercing damage"
 
```

```encounter-table
name: Archon Bastion
creatures:
  - 1: Archon Bastion
```



Rekheps, also known as shield archons, stand against any fiendish onslaughts on Heaven, but occasionally travel to the mortal Universe to protect the weak. Large formations of rekheps are a sight to behold as they lock their shield forms in place to face the wicked.
