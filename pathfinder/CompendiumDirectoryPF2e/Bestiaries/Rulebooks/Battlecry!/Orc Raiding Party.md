---
title: "Orc Raiding Party"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.pC7oMxW93OArImq9" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Orc Raiding Party"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Orc Raiding Party"
level: "Creature 5"

alignment: ""
size: "grg"
trait_01: [[humanoid]]
trait_02: [[orc]]
trait_03: [[troop]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Intimidation: +12"
abilityMods: [5, 4, 4, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +15, __Will__ +12"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, (4 segments); Thresholds 50 (3 segments), 25 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Ferocious Fall"
    desc: "`pf2:r`  The orc raiding party is about to lose a segment due to passing a Hit Point threshold\n* * *\n\n**Effect** The dying orc raiders lash out as they fall. Each enemy in a 5-foot emanation takes 1d6+2 piercing damage (`DC 19 Reflex check` save); this occurs before the raiding party loses a segment."

  - name: "Troop Defenses"
    desc: "  **HP** 75 (4 segments); **Thresholds** 50 (3 segments), 25 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Break Through"
    desc: "`pf2:3`  **Frequency** once per 10 minutes\n* * *\n\n**Effect** The orc raiders exploit a gap in enemy lines. The orc raiding party Strides twice; it can pass through spaces of Medium or smaller creatures but can't end its movement in them. All enemies whose spaces the orc raiding party passed through or were adjacent to at any point during their movement take 1d6+2 piercing damage (`DC 19 Reflex check` save). A creature who critically fails this save is also pushed 5 feet away from the orc raiding party. Break Through damages each creature only once."

  - name: "Iron Rain"
    desc: "`pf2:2`  The orc raiders launch a multitude of javelins at foes in a deadly volley. This volley is a 10-foot burst within 30 feet that deals 3d6 piercing damage with a `DC 19 Reflex check` save. When the orc raiding party is reduced to 2 or fewer segments, this area decreases to a 5-foot burst."

  - name: "Rip Them Up"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The orc raiders batter all enemies in a 5-foot emanation with coordinated knuckle dagger strikes (`DC 19 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6+2 piercing damage\n\n`pf2:2` 2d6+5 piercing damage\n\n`pf2:3` 3d6+7 piercing damage"
 
```

```encounter-table
name: Orc Raiding Party
creatures:
  - 1: Orc Raiding Party
```



Orc raiding parties are feared units whose unrelenting attacks and sheer ferocity make them capable, if not subtle, soldiers. Orc raiders take the duty of carrying their hold's banner into combat with deadly seriousness and will gladly risk grievous injuries to keep their hold's standard flying high.
