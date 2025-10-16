---
title: "Druid Circle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.V2vFgzymDp2wKRwh" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Druid Circle"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Druid Circle"
level: "Creature 12"

alignment: ""
size: "grg"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; "
languages: "Common, Wildsong"
skills:
  - name: "Skills"
    desc: ""
abilityMods: [1, 4, 1, 2, 7, 4]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +19, __Ref__ +22, __Will__ +25"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, (4 segments); Thresholds 140 (3 segments), 70 (2 segments); __Weaknesses__ area damage 10, splash damage 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 210 (4 segments); **Thresholds** 140 (3 segments), 70 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Primal Prepared Spells"
    desc: "DC 32, attack +26; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Control Water|Control Water]]_, _[[Spells/Howling Blizzard|Howling Blizzard]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_; __4th __  _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_; __3rd __  _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Speak with Plants|Speak with Plants]]_\n__Cantrips__  __(6th)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Frostbite|Frostbite]]_, _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Stabilize|Stabilize]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Call Down the Storm"
    desc: "`pf2:2` (air,electricity,primal) The druids summon wind and lightning against all creatures in a 10-foot burst within 80 feet. This storm deals 3d10 electricity damage (`DC 29 Reflex check` save). A creature who fails the save is also pushed 5 feet away from the druid circle. When the druid circle is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Sickle and Staff"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The druids strike out in a coordinated melee attack against all enemies in a 5-foot emanation with a `DC 29 Reflex check` save. The damage dealt depends on the number of actions.\n\n`pf2:1` 2d6 untyped damage\n\n`pf2:2` 4d6+9 untyped damage\n\n`pf2:3` 5d6+13 untyped damage"

  - name: "Troop Spellcasting"
    desc: "  When the druid circle Casts a Spell, its constituent members combine their efforts into casting a more powerful version of the spell than any one member could achieve alone. When Casting a Spell that has an area of a burst, cone, or line and doesn't have a duration, increase the area of that spell. Add 5 feet to the radius of a burst that normally has a radius of at least 10 feet (a burst with a smaller radius is not affected). Add 5 feet to the length of a cone or line that is normally 15 feet long or smaller, and add 10 feet to the length of a larger cone or line."
 
```

```encounter-table
name: Druid Circle
creatures:
  - 1: Druid Circle
```



In their role as protectors of the wild and unspoiled areas of the world, powerful druids might gather together to stand against a particularly heinous threat.
