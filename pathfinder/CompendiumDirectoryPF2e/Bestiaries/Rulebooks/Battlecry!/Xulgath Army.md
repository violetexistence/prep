---
title: "Xulgath Army"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.XZcLHaZP7yt2XU8Q" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Xulgath Army"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Xulgath Army"
level: "Creature 6"

alignment: ""
size: "grg"
trait_01: [[humanoid]]
trait_02: [[troop]]
trait_03: [[xulgath]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Stealth: +13"
abilityMods: [5, 3, 3, 0, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +14, __Will__ +11"
hp: 99
health:
  - name: ""
  - name: HP
    desc: "99, (4 segments); Thresholds 66 (3 segments), 33 (2 segments); __Weaknesses__ area damage 5, splash damage 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Stench"
    desc: " (aura,olfactory) 30 feet `DC 24 Fortitude check`\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

  - name: "Troop Defenses"
    desc: "  Troops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Club Offensive"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The xulgaths make coordinated melee attacks against each enemy in 5-foot emanation, with a `DC 21 Reflex check` save. The damage dealt depends on the number of actions.\n\n`pf2:1` 1d6+1 bludgeoning damage\n\n`pf2:2` 2d6+7 bludgeoning damage\n\n`pf2:3` 2d6+12 bludgeoning damage"

  - name: "Javelin Barrage"
    desc: "`pf2:2`  he xulgaths draw javelins and launch a coordinated barrage at range. This barrage is a 10-foot burst within 30 feet that deals 3d6 piercing damage (`DC 21 Reflex check` save). When the xulgath army is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Rend Flesh"
    desc: "`pf2:2`  The xulgaths concentrate their attacks on a single adjacent enemy, clawing and biting with abandon. That creature takes 3d4+5 slashing damage (`DC 21 Reflex check` save). On a failed save, the creature also takes 1d4 persistent bleed damage."
 
```

```encounter-table
name: Xulgath Army
creatures:
  - 1: Xulgath Army
```



Though most xulgath settlements can be found in the Darklands, these reptilian humanoids sometimes venture to the surface with ill intent. When gathered into an army, xulgaths tear through innocent communities in the name of whatever leader they serve.
