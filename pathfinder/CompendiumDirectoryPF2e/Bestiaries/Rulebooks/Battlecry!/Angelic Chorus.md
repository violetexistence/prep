---
title: "Angelic Chorus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.p8sGnipPHZuoyg9F" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/holy
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Angelic Chorus"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Angelic Chorus"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[holy]]
trait_04: [[troop]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Diabolic, Draconic, Empyrean; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Diplomacy: +25, Performance: +27, Religion: +24"
abilityMods: [2, 5, 3, 3, 4, 7]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +19, __Ref__ +22, __Will__ +25"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, (4 segments); Thresholds 210 (4 segments); Thresholds 140 (3 segments), 70 (2 segments); __Weaknesses__ area damage 10, splash damage 10, unholy 10; __Resistances__ sonic 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Troop Defenses"
    desc: "  **HP** 210 (4 segments); **Thresholds** 210 (4 segments); Thresholds 140 (3 segments), 70 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Divine Innate Spells"
    desc: "DC 19, attack +24; __6th __  _[[Spells/Clear Mind|Clear Mind]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Noise Blast|Noise Blast]]_, _[[Spells/Zealous Conviction|Zealous Conviction]]_; __5th __  _[[Spells/Breath of Life|Breath of Life]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Noise Blast|Noise Blast]]_; __4th __  _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Clear Mind|Clear Mind]]_, _[[Spells/Noise Blast|Noise Blast]]_; __3rd __  _[[Spells/Counter Performance|Counter Performance]]_\n__Cantrips__  __(6th)__ _[[Spells/Courageous Anthem|Courageous Anthem]]_, _[[Spells/Uplifting Overture|Uplifting Overture]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Angelic Messenger_"

  - name: "Admonishing Hymn"
    desc: "`pf2:2` (divine,holy,sonic) The angelic choir raises their voices in song, singing a note that vibrates the very fabric of being. This takes the form of a 15-foot burst within 90 feet that deals 6d6 sonic damage (`DC 29 Fortitude check` save). A creature who critically fails the save is [[Conditions/Deafened|Deafened]] for 1 minute. When the angelic chorus is reduced to 2 segments, this area decreases to a 10-foot burst."

  - name: "Harmonized Spellcasting"
    desc: "  When the angelic chorus Casts a Spell, their constituent members combine their efforts into casting a more powerful version of the spell than any one member could achieve alone. When Casting a Spell that deals sonic damage, that spell gains a status bonus to damage equal to its rank."

  - name: "Righteous Clamor"
    desc: "`pf2:1` (holy,magical) **Frequency** once per round\n* * *\n\n**Effect** With sonorous shouts, the angelic chorus lashes out with their fists in a coordinated melee attack against each enemy in a 5-foot emanation (`DC 29 Reflex check` save). The damage depends on the number of actions\n\n`pf2:1` 1d8 bludgeoning damage plus 1d6 sonic damage\n\n`pf2:2` 2d8+7 bludgeoning damage plus 2d6 sonic damage\n\n`pf2:3` 3d8+10 bludgeoning damage plus 2d6 sonic damage"
 
```

```encounter-table
name: Angelic Chorus
creatures:
  - 1: Angelic Chorus
```



While choral angels are content to sing their hymns in Nirvana, they must sometimes take to the mortal realm to provide needed succor for those engaged in righteous battle against the wicked. An angelic chorus often acts as support for armies who have gained the favor of the celestial realms.
