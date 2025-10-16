---
title: "Sky Fisher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.howl-of-the-wild-bestiary.Actor.DiU1sOTZHKbSQoKD" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Sky Fisher"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Sky Fisher"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +21, Stealth: +23"
abilityMods: [5, 7, 7, -4, 0, -3]
speed:  fly 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +22, __Will__ +15"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  precision; __Weaknesses__ piercing 7, slashing 7; __Resistances__ bludgeoning 14, poison 14"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Transparency"
    desc: "  Unless it has fed recently, the sky fisher is naturally [[Conditions/Invisible|Invisible]]. Using non-hostile actions does not cause the sky fisher to become [[Conditions/Hidden|Hidden]]. When it takes a hostile action of any kind, the sky fisher is hidden instead of [[Conditions/Undetected|Undetected]] until the start of its next turn, as the vague outline of its many tendrils temporarily becomes faintly visible."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stinging Tentacle"
    desc: "+24 (agile, reach 30 feet)\n__Damage__  2d8 + 8 bludgeoning plus *grab,sky-fisher-venom*"

  - name: "Abduct"
    desc: "`pf2:1` (attack) The sky fisher reels in a target [[Conditions/Grabbed|Grabbed]] by its tentacles, pulling them into an adjacent space, and then attempts to [[Bestiary Ability Glossary/Swallow Whole|Swallow them Whole]] (Large, 3d8+12 acid, Rupture 25). The sky fisher can only use Swallow Whole when using Abduct."

  - name: "Enzymic Vent"
    desc: "`pf2:2` (poison) The sky fisher vents flesh-eating enzymes into the air, dealing 3d6 persistent acid damage and 3d6 persistent bleed damage in a 20-foot emanation (`DC 25 Reflex check` save). It can't use Enzymic Vent again for 1d4 rounds."

  - name: "Jet"
    desc: "`pf2:2` (move) The sky fisher quickly expels some of its gases to move swiftly through the air, Flying up to 100 feet in a straight line; this movement doesn't trigger reactions."

  - name: "Sky Fisher Venom"
    desc: " (poison) **Saving Throw** `DC 25 Fortitude check`\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and can't speak above a whisper (1 round)\n\n**Stage 2** 3d8 poison damage, [[Conditions/Clumsy|Clumsy 2]], and can't speak (1 round)\n\n**Stage 3** 3d10 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[Actions/grapple|grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sky Fisher
creatures:
  - 1: Sky Fisher
```



The sky fisher is an unusual aerial predator, mostly found in tropical jungle regions but occasionally seen as far north as Varisia. Naturalists believe it's a distant relative of the jellyfish that has evolved into a new ecological niche through prolonged exposure to elemental energies from the Plane of Air. That the biggest, most aggressive sky fishers are found (and thought to have originated) near powerful loci of elemental air, such as in Garund's Terwa Uplands or around the Eye of Abendego, lends further credence to this theory.

In appearance, a sky fisher resembles an enormous jellyfish, its many dangling tendrils hanging beneath a clear bulbous body. Although its appearance is quite difficult to accurately determine, as its natural transparent form is almost completely [[Conditions/Invisible|Invisible]], its inside contain a complex chemical factory that produces lighter-than-air gases, paralyzing toxins, and flesh-eating enzymes. These enzymes are highly potent and often desired by toxicologists due to their unique properties. The creature hunts by hovering just above the forest canopy, using eye-like clusters on the ends of its tentacles as a kind of inverted periscope. When it spots prey, it floats close and waits for an opportune moment to sting. Then, as paralysis takes hold, the sky fisher hoists its meal into the sky to slowly consume it. Inside, enzymes break down the dead or paralyzed victims into a bloody slurry.

A recently fed sky fisher can always be quickly identified by the looping coils of blood that circulate through its body—a beautiful, if terrible, sight.
