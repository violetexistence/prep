---
title: "Fleshwarp Amalgam"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.xEWRFIUNr52EmwVM" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/mindless
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Fleshwarp Amalgam"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Fleshwarp Amalgam"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[mindless]]
trait_03: [[troop]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common, Sakvroth; (cant speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +18, Intimidation: +16"
abilityMods: [6, 2, 5, -5, 0, 0]
speed: 30 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +19, __Ref__ +14, __Will__ +13"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, (4 segments); Thresholds 90 (3 segments), 45 (2 segments); __Immunities__  acid,  mental; __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Brutal Retaliation"
    desc: "`pf2:r`  **Trigger** The fleshwarp amalgam loses a segment due to passing a Hit Point threshold\n* * *\n\n**Effect** The fleshwarp amalgam lashes out in retaliation. Each enemy in a 5-foot emanation takes 2d10+6 untyped damage (`DC 23 Reflex check`). A creature who fails the save is also pushed 5 feet away from the amalgam."

  - name: "Troop Defenses"
    desc: "  **HP** 135 (4 segments); **Thresholds** 90 (3 segments), 45 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Acid Spray"
    desc: "`pf2:2` (acid) The fleshwarp amalgam sprays acid from their various orifices, combining the streams into a powerful spray. This acid spray is a 10-foot burst that deals 3d8 acid damage (`DC 23 Reflex check` save) within 60 feet. A creature who critically fails their saving throw takes 1d8 persistent acid damage. When the troop is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Frenzy of Tentacles and Claws"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The fleshwarps make wild melee attacks against each enemy in a 5-foot emanation (`DC 23 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d10 untyped damage\n\n`pf2:2` 2d10+6 untyped damage\n\n`pf2:3` 2d10+11 untyped damage"

  - name: "Many-Limbed Stride"
    desc: "  While moving on land, the fleshwarp amalgam ignores the effects of non-magical difficult terrain."
 
```

```encounter-table
name: Fleshwarp Amalgam
creatures:
  - 1: Fleshwarp Amalgam
```




