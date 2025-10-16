---
title: "Holdfast"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.howl-of-the-wild-bestiary.Actor.VhS8LupBXLEcuztc" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Holdfast"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Holdfast"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision, Scent (Imprecise) 30 Feet, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +11, Stealth: +12"
abilityMods: [5, 4, 3, -4, 2, 0]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +12, __Will__ +8"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hold Tight"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the holdfast's jaws takes damage from another creature's Strike\n* * *\n\n**Effect** The holdfast Constricts the creature in its jaws."

  - name: "Lithe"
    desc: "  A holdfast treats any tight space it can barely fit its head in or wider as difficult terrain and doesn't need to [[Actions/Squeeze|Squeeze]] to move through it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 (unarmed)\n__Damage__  2d6 + 5 piercing plus *Grab*"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+13 (agile, unarmed)\n__Damage__  2d4 + 5 slashing"

  - name: "Burst from Below"
    desc: "`pf2:1`  The holdfast Burrows and then Strikes. If the holdfast began this movement [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+2 piercing plus crush throat, `DC 21 Fortitude check`\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crush Throat"
    desc: "  When a creature fails a save against the holdfast's Constrict, the creature's throat is held tight, stopping them from speaking as long as they're [[Conditions/Grabbed|Grabbed]]. This prevents the creature from casting spells with vocal incantations, as well as from using many sonic or auditory abilities."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Holdfast
creatures:
  - 1: Holdfast
```



A sleek body, large talons, and keen senses make the holdfast an expert hunter, far deadlier than its small size might indicate. It typically approaches prey from below, then pounces in a flurry of teeth and talons, trying to crush the target's windpipe with its powerful jaws. This ambush strategy is further aided by its dappled gray fur, camouflaging it against the rocky terrain of its native habitat. Today, holdfasts have spread far, often because of orc holds adopting them as hunting companions. This has led to tension with other peoples, who often find holdfasts too difficult to work with and consider them an invasive species—even gnomes and druids who can speak with holdfasts find them distractable and murderously energetic.

Although holdfasts watch over their litters very carefully, adults avoid each other outside of their short mating season. Despite this antipathy for others of their kind, holdfasts often trail other species of predators, acting as opportunistic scavengers. This typically ends with the holdfast bullying the other creature and stealing the greater share of any kill, but it can develop into a mutualistic arrangement. Many holdfasts have been observed hunting alongside eagles and other birds of prey, driving underground creatures to the surface for the birds to pick off.

Holdfasts are difficult to contain, sliding through tiny openings and digging under fences, meaning proper enclosures must be made of stone or metal on all sides. Some orc communities instead lay out humane traps when their hunting parties are needed, using favorite treats as bait. In the orc-run nation of Belkzen, overlord Ardax the White-Hair's chief animal handler claims to have a unique and confidential training process that curbs the holdfasts' impulse to escape, but other handlers have yet to uncover or replicate it. In the Gravelands, the major orc communities face the unwelcome intrusion of undead headed by the Whispering Tyrant. While they maintain the original bond with holdfasts as hunting partners, the goal has changed from providing subsistence to eradicating undead.
