---
title: "Speiroikos"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.myth-speaker-bestiary.Actor.I8RBVY3fsLsBDljf" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Speiroikos"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #216: The Acropolis Pyre"
name: "Speiroikos"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[troop]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: "Iblydan"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +7, Warfare Lore: +9"
abilityMods: [4, 3, 3, 1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder #216: The Acropolis Pyre_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +8, __Will__ +6"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, Thresholds 34 (3 segments), 17 (2 segments); __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ area damage 3, splash damage 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Diverted Fury"
    desc: "  The speiroikos' aggression can be redirected against their own numbers. A creature within 30 feet of the speiroikos can take an action to throw a small object such as a rock among the troop, attempting a `DC 17 Deception check` check; this action has the manipulate trait. On a success, the troop deals its two-action Dory Strike damage to itself on its next round, taking no other actions."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  Troops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "[[Bestiary Ability Glossary/Troop Movement|Troop Movement]]"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Dory Strike"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The speiroikos make a melee attack against each enemy in its space and in a 10-foot emanation (`DC 17 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d6 piercing damage\n\n`pf2:2` 1d6+6 piercing damage\n\n`pf2:3` 2d6+6 piercing damage"

  - name: "Dragonhide"
    desc: "`pf2:1`  The speiroikos channel the power of their progenitor dragon to grow thick, scaly hides. Until the end of their next turn, they gain a +1 circumstance bonus to AC, and they reduce their weaknesses to area damage and splash damage by 2."

  - name: "Kestros Volley"
    desc: "`pf2:2`  The speiroikos let loose a flurry of heavy darts flung from slings. The volley is a 10-foot burst within 60 feet that deals 1d8 piercing damage (`DC 17 Reflex check` save) plus 1 bleed damage. When the speiroikos are reduced to 2 or fewer segments, this area decreases to a 5-foot burst."
 
```

```encounter-table
name: Speiroikos
creatures:
  - 1: Speiroikos
```



Speiroikos are born of an unusual ritual in which dragon teeth are sown in the ground, giving rise to a legion of fierce warriors formed of earth. Magic items to summon speiroikos also exist and, on rare occasions, they can arise spontaneously after a dragon is slain, and its body decomposes into the soil.

At first glance, a speiroikos looks like a normal humanoid, though close inspection reveals their skin to have a clay-like texture and their teeth to be draconic fangs. They eagerly follow the one who crafted them into battle and obey their creator's orders without question. One might expect them to be perfect soldiers, but they're prone to fighting among themselves if provoked. Typically, speiroikos last only as long as there's a battle to fight, disintegrating back into dirt once hostilities conclude. Some canny creators manage to prolong their existence by hurrying them from one battle to another.

## Wandering Speiroikos

On rare occasions, a surviving member of a speiroikos troop will maintain its existence after battle, gaining full autonomy; this occurs more often in those created spontaneously. Such survivors often experience an existential crisis, having previously existed only to fight. Some wander the world seeking combat, while others attempt to blend in with humanoid societies and find new aspirations.
