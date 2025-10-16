---
title: "Skeleton Mob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.qjCFbg7IB5NDbMOW" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Skeleton Mob"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Skeleton Mob"
level: "Creature 6"

alignment: ""
size: "grg"
trait_01: [[mindless]]
trait_02: [[skeleton]]
trait_03: [[troop]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13"
abilityMods: [4, 2, 1, -5, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +14, __Will__ +11"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90, (4 segments); Thresholds 160 (3 segments), 80 (2 segments); __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ area damage 7, splash damage 7; __Resistances__ cold 7, electricity 7, fire 7, physical 7, slashing 7"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 240 (4 segments); **Thresholds** 160 (3 segments), 80 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Ossuary Storm"
    desc: "`pf2:2`  The skeleton mob hurls skulls and fragments of bone in a 10-foot burst within 30 feet. This attack deals 3d6 piercing damage (`DC 21 Reflex check` save). When the skeleton mob is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Rattling Bones"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The skeletons engage using their claws and broken bones to attack each enemy in a 5-foot emanation, with a `DC 21 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d4+1 piercing damage\n\n`pf2:2` 2d4+7 piercing damage\n\n`pf2:3` 3d4+10 piercing damage"
 
```

```encounter-table
name: Skeleton Mob
creatures:
  - 1: Skeleton Mob
```



To the morbid, a battlefield is no more than a garden of corpses. Sometimes, either through the magic of a necromancer or through an unfortunate pooling of void energy, these bodies rise up as broken and battered skeletons. While some of these skeletons are far from whole, they can still pose a significant threat.
