---
title: "Sinswarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.DZiYwwjNKlAlyNU2" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Sinswarm"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Sinswarm"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[troop]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Aklo, Thassilonian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +20, Survival: +17"
abilityMods: [6, 3, 4, 1, 2, 1]
speed: 30 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +18, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, (4 segments); Thresholds 100 (3 segments), 50 (2 segments); __Immunities__  controlled; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ mental 10"
abilities_top:
  - name: ""

  - name: "Sin Scent"
    desc: "  A sinswarm can smell creatures reflecting any one of the seven primary sins as the scent ability. The GM determines which creatures are appropriately sinful."

abilities_mid:
  - name: ""
  - name: "Reactive Attack"
    desc: "`pf2:r`  **Trigger** A creature within a 5-foot emanation of the sinswarm uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The sinswarm lashes out at the triggering creature, dealing 2d8+9 piercing damage (`DC 25 Reflex check` save). If the creature critically fails the save and the trigger was a manipulate action, that action is disrupted."

  - name: "Troop Defenses"
    desc: "  **HP** 150 (4 segments); **Thresholds** 100 (3 segments), 50 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Sinful Assault"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The sinswarm makes a coordinated attack against each enemy in a 5-foot emanation, with a `DC 25 Reflex check` save. The damage depends on the number of actions.\n\n`pf2:1` 1d8+2 piercing damage\n\n`pf2:2` 2d8+9 piercing damage plus sinful bite\n\n`pf2:3` 3d8+11 piercing damage plus sinful bite"

  - name: "Sinful Bite"
    desc: " (arcane,emotion,mental) A creature bitten by a sinspawn must attempt a `DC 28 Will check` save as it is assailed by sinful thoughts. The sinswarm can't inflict the same sin effect on multiple targets in the same round until it has inflicted all seven sins at least once.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature is sickened 2 and takes one of the following additional effects, chosen by the GM:\n\n*   [[Conditions/Enfeebled|Enfeebled 2]] for 1 minute (envy)\n    \n*   [[Conditions/Drained|Drained 1]] (gluttony)\n    \n*   [[Conditions/Clumsy|Clumsy 2]] for 1 minute (greed)\n    \n*   [[Conditions/Stupefied|Stupefied 2]] for 1 minute (lust)\n    \n*   [[Conditions/Clumsy|Clumsy 1]] and [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute (pride)\n    \n*   –10-foot status penalty to all Speeds for 1 minute (sloth) [[Bestiary Effects/Effect_ Sinful Bite|Effect: Sinful Bite]]\n    \n*   drained 1 and enfeebled 1 for 1 minute (wrath)"
 
```

```encounter-table
name: Sinswarm
creatures:
  - 1: Sinswarm
```



Sinspawn, monstrosities of twisted humanoid flesh, were created ages ago by the runelord Alaznist to serve as shock troops. Hateful even toward their own kind, sinspawn usually band together only in small, isolated cults, although powerful beings are occasionally able to coerce greater numbers of these slavering horrors to join forces as uniquely bloodthirsty and destructive mobs.
