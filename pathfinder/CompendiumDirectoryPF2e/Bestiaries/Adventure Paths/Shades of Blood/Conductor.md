---
title: "Conductor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Compendium.pf2e.shades-of-blood-bestiary.Actor.Y1uFZHLnPjMyLvHS" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Conductor"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #215: To Blot Out the Sun"
name: "Conductor"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[fiend]]
trait_02: [[velstrac]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Greater Darkvision"
languages: "Chthonian, Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +14, Deception: +19, Diplomacy: +19, Intimidation: +19, Medicine: +17, Performance: +23, Religion: +17, Stealth: +19, Torture Lore: +16"
abilityMods: [3, 6, 5, 3, 5, 6]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #215: To Blot Out the Sun_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +21, __Will__ +18; +1 status to all saves vs. magic"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, regeneration 10 (deactivated by holy or silver; __Immunities__  cold; __Weaknesses__ holy 10, silver 10; __Resistances__ sonic 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Conductor's Baton"
  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Holy or Silver]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Horrifying Accompaniment"
    desc: " (auditory,aura,divine,emotion,fear,mental) 30 feet. When a creature ends its turn in the aura, it hears every scream the velstrac conductor's victims have ever uttered. The creature must succeed at a `DC 25 Will check` save or become [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 4]] on a critical failure)."

  - name: "Sonic Redirection"
    desc: "`pf2:r` (divine,sonic) **Trigger** A creature targets the velstrac conductor with an auditory or sonic effect or includes the conductor in the area of an auditory or sonic effect\n* * *\n\n**Effect** The conductor sings a note that resonates with the triggering effect, redirecting it to the triggering creature. The triggering creature becomes the target of the triggering effect, instead of the conductor."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile, finesse, magical, unarmed, unholy)\n__Damage__  4d6 + 7 slashing"

  - name: "**Melee** `pf2:1` Conductor&#x27;s Baton"
    desc: "+19 (agile, finesse, magical, unholy)\n__Damage__  3d4 + 7 piercing 2d6 spirit"

  - name: "**Ranged** `pf2:1` Pinpoint Shriek"
    desc: "+19 (divine, range increment 90 feet, sonic)\n__Damage__  4d6 sonic"

  - name: "Divine Innate Spells"
    desc: "DC 28, attack +20; __3rd __  _[[Spells/Haste|Haste]]_; __2nd __  _[[Spells/Darkness|Darkness]]_\n__Constant__  __(4th)__ _[[Spells/Fly|Fly]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,emotion,fear,mental) The velstrac conductor stares at a creature they can see within 30 feet. The creature must immediately attempt a Will save against the velstrac conductor's horrifying accompaniment aura. In addition, if the creature was already frightened, on a failed save the creature takes 1d6 persistent mental damage. After attempting this save, the creature is then temporarily immune for 1 hour."

  - name: "Scream for Me"
    desc: "`pf2:1` (divine,mental,sonic) **Frequency** once per round\n* * *\n\n**Effect** With a horrifying flourish and hungry smile, the velstrac conductor points their baton at a creature within 100 feet, compelling them to scream. The creature must attempt a `DC 28 Will check` save. On a failure, they scream, taking 4d6 mental damage (8d6 mental on a critical failure) and dealing 2d6 sonic damage to all creatures in a 20-foot emanation (`DC 28 Fortitude check` save).\n\nInstead of targeting one creature, the conductor can choose to target all creatures in range that were compelled to scream by this ability last round."

  - name: "Unholy Exaltation"
    desc: "`pf2:2` (divine,sonic,unholy) The conductor lets out a terrible scream of joy, dealing 10d6 sonic damage to all creatures in either a 30-foot cone or a 90-foot line (`DC 28 Will check` save). Holy creatures that fail this save are also [[Conditions/Sickened|Sickened 2]]. The conductor can't use Unholy Exaltation again for 1d4 rounds."
 
```

```encounter-table
name: Conductor
creatures:
  - 1: Conductor
```



Velstracs arise from the souls of the most extreme masochistic or sadistic mortals who are judged by Pharasma and then sent on to the Netherworld. The fiends come in many horrific forms, which usually manifest in twisted display of their vile predilections in life, ranging from the low-ranking augurs to the maestros of suffering and mutilation called eremites. The process of transformation warps the velstrac's soul step by step, with other velstracs conveying their new members through untold chambers of pain among the dark reaches of the Netherworld. The velstracs are led by the pinnacles of their kind, a group of nine powerful fiends known as velstrac demagogues.

Once their transformation is complete, velstracs emerge as twisted artists who wield pain and despair like an instrument. They crave sensation, the more vile and horrifying, the better. They claim that this outlook is the one true path to perfection of the mind, body, and spirit, but in truth their administrations only deal out suffering and mutilation. Their corrupt attempts at perfection aren't limited to their victims, who they torture for as long as they possibly can until their bodies or minds fail, but also applied to themselves, testing their own resolve in a crucible of pain.

Velstracs feature in this adventure in a couple of ways. When Nizca and Deg failed to veil the sun in shadows using the shadow beacon, portions of the Netherworld overlaid En-Gokal. The velstracs, led by the velstrac conductor Jubilant, passed traveled from their shadowy realm into the mortal world of the Universe. When they arrived, they were amused by the predations of the vampires and their tenacity to hold the ruined prison, but they were especially delighted by Nizca, with whom they felt a kinship in shadow due to Nizca being an ancient strigoi—a perfect blend of shadow and vampire. Jubilant and their fellow velstracs obviously favored the plan to bring eternal darkness to Golarion, and thus they support Nizca in completing their horrifying mission, but who can say how long that support will last once the plan is complete?

In addition to the most prevalent influence of velstracs in the Ebon Tower, they also play another role for the primary antagonist, Nizca. As mentioned in the campaign, one of Nizca's motivations for escaping En-Gokal is to reunite with their lover from the time before Earthfall. A cruel yet handsome man, Lograsi was a worshipper of Aroggus, a powerful velstrac demagogue with the portfolios of possibility, revenge, and sanctuary. This connection was part of Nizca's reason to trust in Jubilant and their group of velstracs, knowing that her distant lover was of the faith.

## Velstrac Conductor

Conductors are velstracs who believe screams of anguish to be the ultimate form of musical expression. These sadistic musicians compose "joyous symphonies" from the agonized howling of their tortured, captive choirs.

## Instruments

Conductors go to great lengths to acquire the finest instruments for their choirs, judging an individual singer's worth by their tone, emotion, endurance, and responsiveness. Vocalists who don't measure up to a conductor's standards are either played to death or passed on to other "less discerning" velstracs. Cherished instruments can expect to live a long, tortuous existence in a conductor's choir, receiving the best medical attention after each performance—at least until their voice gives out.

## Tortured Friendships

Velstrac conductors are fairly amiable among their kind and often work with other velstracs. They particularly get along well with ostiarius velstracs and velstrac evangelists, who they tend to boss around. Though they find sacristans piteous, they're intrigued by their Shadow Scream ability.
