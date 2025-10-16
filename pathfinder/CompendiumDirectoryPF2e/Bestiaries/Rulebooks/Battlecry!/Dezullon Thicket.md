---
title: "Dezullon Thicket"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.battlecry-bestiary.Actor.mKQXrEpheSCjgJt8" 
tags:
  - pf2e/creature/type/plant
  - pf2e/creature/type/troop
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Dezullon Thicket"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Battlecry!"
name: "Dezullon Thicket"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[plant]]
trait_02: [[troop]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +27, Stealth: +29"
abilityMods: [6, 8, 4, -4, 3, -1]
speed: 25 feet
sourcebook: "_Pathfinder Battlecry!_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +28, __Will__ +23"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, (4 segments); Thresholds 180 (3 segments), 90 (2 segments); __Weaknesses__ area damage 15, splash damage 15; __Resistances__ acid 20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Regeneration"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Regrowth"
    desc: "  When the dezullon thicket's regeneration raises its Hit Points above a listed threshold after losing a segment for dropping below it, the thicket immediately regains that lost segment."

  - name: "Troop Defenses"
    desc: "  **HP** 180 (4 segments); **Thresholds** 180 (3 segments), 90 (2 segments)\n\nTroops are composed of many individuals, represented by four \"segments\" on a battle grid. Each segment is 10 feet on each side and as tall as the individual members of the troop. Segments must remain contiguous. Each one has to share at least 5 feet of one of its edges with another segment—being adjacent on a diagonal isn't sufficient! You can measure flanking, cover, and the like using the center of any segment.\n\nA troop has two Hit Point thresholds in its HP entry and loses segments as it crosses thresholds. Typically, the higher threshold is at 2/3 of the troop's maximum Hit Points and the lower is at 1/3 of its maximum. Once the troop drops below the higher threshold, it loses one segment, leaving three segments (12 squares) remaining and setting the first threshold as the troop's new maximum Hit Points. This repeats when the troop drops below the lower threshold, leaving two segments (8 squares). At 0 Hit Points, the troop disperses entirely, with the few remaining members surrendering, [[Conditions/Fleeing|Fleeing]], or easily dispatched, as determined by the GM. Typically the creature who caused the troop to lose a segment decides which to remove, or the GM decides when a specific creature wasn't responsible. To restore lost segments and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen.\n\nTroops are typically immune to non-damaging effects that target a single creature, such as a [[Spells/Charm|Charm]] spell or the [[Actions/Demoralize|Demoralize]] action. An ability that can target 5 or more creatures can target an entire segment, increasing to two segments if it can target 10 or more creatures and to the entire troop if it can target 20 or more creatures. An ability that affects all creatures in a certain range affects all segments in range (make any checks or saves separately for each segment). As examples, an 8th rank _charm_ spell (with 10 targets) can affect two segments, and an ability that Demoralizes all creatures within 30 feet of you would affect all segments that are fully within that range. A non-damaging ability that would prevent a segment from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more removes the segment entirely. The troop loses a number of HP required to bring it to the next threshold. If an ability both deals damage and has a non-damaging effect, apply the damage then the rest of the effect."

  - name: "Troop Movement"
    desc: "  Whenever a troop moves, you move one of its segments and the other segments follow behind it. At the end of the movement, you can group the other segments adjacent to the one you moved as you see fit, provided none of them moves farther than the moving segment. If you choose not to move the troop any distance, you can instead reshape the position of all the segments as long as one stays in place."

attacks:
  - name: ""

  - name: "Acid Rain"
    desc: "`pf2:2`  The dezullon thicket discharges a cascade of acidic digestive juices as a ranged attack, dealing 6d6 acid damage in a 10-foot burst within 30 feet (`DC 33 Reflex check` save) and exposing any creature struck to amnesia venom. When the thicket is reduced to 2 segments, this area decreases to a 5-foot burst."

  - name: "Amnesia Venom"
    desc: " (mental,poison) **Saving Throw** `DC 33 Fortitude check`\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** [[Conditions/Confused|Confused]], [[Conditions/Off-Guard|Off-Guard]], and [[Conditions/Clumsy|Clumsy 3]] (1 round)\n\n**Stage 4** as Stage 3 and permanently forget the last hour (1 round)"

  - name: "Constrict"
    desc: "`pf2:1`  1d10+6 bludgeoning, `DC 36 Fortitude check`\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Root"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the dezullon thicket appears to be a field of normal pitcher plants. It has an automatic result of 49 (53 in forests or swamps) on Deception checks and DCs to pass as a grove of non-creature plants."

  - name: "Thrashing Vines"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The thicket makes a melee attack against each enemy within a 5-foot emanation (`DC 33 Reflex check` save). The damage depends on the number of actions.\n\n`pf2:1` 1d8+3 bludgeoning plus 1d6 acid\n\n`pf2:2` 2d8+11 bludgeoning plus 2d6 acid and Mass Improved Grab\n\n`pf2:3` 3d8+12 bludgeoning plus 3d6 acid and Mass Improved Grab"

  - name: "Mass Improved Grab"
    desc: "  **Trigger** A creature fails or critically fails their Reflex save against the dezullon thicket's Thrashing Vines\n* * *\n\n**Effect** The dezullon thicket attempts an Athletics check to [[Actions/grapple|grapple]] the triggering creature. A dezullon thicket can Grapple as many creatures as it has remaining segments, though it needs to spend an action to extend the duration on subsequent rounds. These attempts neither apply nor count toward the creature's multiple attack penalty."
 
```

```encounter-table
name: Dezullon Thicket
creatures:
  - 1: Dezullon Thicket
```




