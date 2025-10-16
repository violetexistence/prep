---
title: "Giant Ant Army"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.pY9fEPDxG925iivp" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Giant Ant Army"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Giant Ant Army"
level: "Creature 7"

alignment: ""
size: "grg"
trait_01: [[animal]]
trait_02: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17, Survival: +15"
abilityMods: [6, 2, 6, -4, 2, -4]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +14, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, (4 segments); Thresholds 80 (3 segments), 40 (2 segments); __Weaknesses__ area damage 7, splash damage 7"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 120 (4 segments); **Thresholds** 80 (3 segments), 40 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Giant Ant Venom"
    desc: "  **Saving Throw** `DC 24 Fortitude check`\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d8 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "Grasping Mandibles"
    desc: "`pf2:1`  **Requirements** The giant ant army's last action was a Mandible Frenzy that at least one creature failed their save against or the giant ant army has at least one creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after Grasping Mandibles, the giant ant army can attempt an Athletics check to [[Actions/grapple|grapple]], comparing the result to the Fortitude DC of each creature who failed its saving throw, up to as many creatures as the giant ant army has remaining segments. The giant any army can instead use Grasping Mandibles to choose one creature it's grabbing or restraining to automatically extend that condition to the end of the army's next turn."

  - name: "Haul Away"
    desc: "`pf2:1`  **Requirements** The giant ant army has at least one creature [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The army Strides up to its Speed, carrying any restrained creatures with it. If the creature is Gargantuan, the giant ant army is [[Conditions/Encumbered|Encumbered]]."

  - name: "Mandible Frenzy"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The army makes a savage bite attack against each enemy in a 5-foot emanation (`DC 22 Reflex check` save). The damage dealt depends on the number of actions.\n\n`pf2:1` 1d8 slashing damage plus Grasping Mandibles\n\n`pf2:2` 2d8+6 slashing damage plus Grasping Mandibles\n\n`pf2:3` 2d8+11 slashing damage"

  - name: "Overwhelm"
    desc: "`pf2:2`  The giant ant army swarms over a Large or larger creature that it has [[Conditions/Grabbed|Grabbed]], pinning the creature in place and causing it to become [[Conditions/Restrained|Restrained]] until the start of the giant ant army's next turn or until it Escapes. A creature that begins its turn restrained by the army is repeatedly stung by the clinging ants, automatically taking 2d6 piercing damage and suffering the effects of giant ant venom."
 
```

```encounter-table
name: Giant Ant Army
creatures:
  - 1: Giant Ant Army
```



Like their tiny counterparts, colonies of giant ants often form vast armies that launch regular campaigns into the lands surrounding their nests to forage for food and expand their territory. Though their primary targets are usually rival colonies, a giant ant army that happens upon a humanoid settlement will not hesitate to overrun and strip it of resources to bring back to their queen, taking a particular interest in the settlement's former inhabitants.
