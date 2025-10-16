---
title: "Simandu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.curtain-call-bestiary.Actor.6guVWljIlk02aam7" 
tags:
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/19
  - remaster
statblock: inline
name: "Simandu"
level: 19
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Simandu"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision"
languages: "Aklo, Common, Diabolic, Fey; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +33, Deception: +36, Diplomacy: +34, Intimidation: +34, Society: +32, Stealth: +36, Norgorber Lore: +32, Vyre Lore: +34"
abilityMods: [6, 7, 6, 5, 8, 7]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +29, __Ref__ +34, __Will__ +33"
hp: 355
health:
  - name: ""
  - name: HP
    desc: "355; __Weaknesses__ cold iron 15; __Resistances__ poison 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortsword|+2 Greater Striking Keen Wounding Dawnsilver Shortsword]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Whispered Secrets"
    desc: " (aura,mental,occult) 30 feet. The soft sound of whispering fills the area, and those in the area hear their own voice whispering among the voices. A creature that enters the area or begins their turn in the area must attempt a `DC 38 Will check` save. On a failure, they become distracted by the conviction that their own voice is whispering out their secrets, and the creature becomes [[Conditions/Off-Guard|Off-Guard]] until the start of their next turn."

  - name: "Darting Legs"
    desc: "`pf2:r`  **Requirements** The jorogumo has their spider legs extended or has Changed Shape\n\n**Trigger** The jorogumo is targeted with an attack\n* * *\n\n**Effect** The jorogumo raises a leg, gaining a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (unarmed)\n__Damage__  3d12 + 14 piercing plus *jorogumo-venom*"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+36 (agile, finesse, magical, versatile s)\n__Damage__  1d6 bleed 3d6 + 14 piercing"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+34 (range increment 60 feet)\n__Damage__ "

  - name: "Occult Innate Spells"
    desc: "DC 34, attack +26; __9th __  _[[Spells/Speak with Animals|Speak with Animals (Constant, Spiders Only)]]_, _[[Spells/Summon Animal|Summon Animal (Spiders Only)]]_; __8th __  _[[Spells/Charm|Charm (x3)]]_, _[[Spells/Outcast's Curse|Outcast's Curse (x3)]]_, _[[Spells/Pinpoint|Pinpoint]]_, _[[Spells/Quandary|Quandary]]_, _[[Spells/Suggestion|Suggestion (x3)]]_; __7th __  _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Mind Reading|Mind Reading (At Will)]]_\n__Constant__  __(9th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The jorogumo takes on the appearance of any Small or Medium spider. This doesn't change their Speed or Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Jorogumo Venom"
    desc: " (incapacitation,poison) **Saving Throw** `DC 41 Fortitude check`\n* * *\n\n**Maximum Duration** 4 hours\n\n**Stage 1** 3d6 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)\n\n**Stage 3** 4d6 poison damage and Stupefied 2 (1 round)\n\n**Stage 4** [[Conditions/Paralyzed|Paralyzed]] for 1d4 hours"

  - name: "Sneak Attack"
    desc: "  Simandu deals 3d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."

  - name: "Spider Legs"
    desc: "`pf2:1` (concentrate,occult,polymorph) **Requirements** The jorogumo is in humanoid form\n* * *\n\n**Effect** Eight large spider legs sprout from the jorogumo's back, granting them a 40-foot climb Speed and allowing them to use the Darting Legs reaction."

  - name: "Web Trap"
    desc: "  A creature hit by the jorogumo's web attack is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface, preventing the creature from moving.\n\nThe DC to [[Actions/Escape|Escape]] or [[Actions/Force Open|Force Open]] the web trap is 34."

  - name: "Whispered Revelation"
    desc: "`pf2:2` (incapacitation,mental,occult) Simandu whispers an overwhelming secret to an adjacent creature—the nature of the secret is so staggering that the creature's mind immediately recoils from the truth and forgets it; the creature must then attempt a `DC 41 Will check` save.\n* * *\n\n**Critical Success** The creature is [[Conditions/Off-Guard|Off-Guard]] until the end of Simandu's turn.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 3]].\n\n**Critical Failure** The creature becomes [[Conditions/Paralyzed|Paralyzed]] for 1 minute. At the end of each of its turns, it can attempt a new `DC 41 Will check` save to end this effect early."
 
```

```encounter-table
name: Simandu
creatures:
  - 1: Simandu
```


Female variant jorogumo

Appearing as beautiful, well-dressed humans, jorogumo lurk in the high mountains and prey on travelers. These evil creatures can fully change into a giant spider or sprout spider legs from their backs, and they often keep giant spiders as pets. Jorogumo usually eat their prey, but some humanoids meet an even more gruesome fate as living incubators for jorogumo eggs. Though most jorogumos are solitary creatures, some have taken up worship of Norgorber and serve as valuable allies to thieves' guilds following that god's guise as the Gray Master.
