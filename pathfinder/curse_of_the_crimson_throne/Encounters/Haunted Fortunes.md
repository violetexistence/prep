```pf2e-stats
# Fishery in Flames
## Hazard 0
---
==environmental==

**Stealth** DC 16 (trained)

**Description** The rotten wood and haphazard structure of the Old Fishery can't hold up under the strain of combat, fire, or sabotage. Once triggered, the floor begins to collapse in a cascading chain reaction, threatening to dump everyone in the warehouse into the river below--or worse, into the pen of Gaedren's pet crocodile.

---

**AC** 16; **Fort** +3, **Ref** +5

**HP** 8; **Immunities** object immunities, precision damage

**Disable** DC 19 Survival (trained) to safely extinquish the flames or deal any amount of cold damage to the hazard without triggering it, DC 15 Crafting or Engineering/Carpentry Lore (trained) to identify weak points and stabilize the floor. If the action taken to disable is successful and not already an attack that deals cold damage, the hazard takes 1d6 damage.

**Structural Stress** `[reaction]` **Trigger** A PC Strides more than half speed or uses a Strike action within the hazard area; **Effect** The Fishery must attempt a DC 14 Fortitude save:
- **Fail** A 5-foot section of the floor suffers catastrophic collapse.
- **Crit Fail** A 10-foot section of the floor suffers catastrophic collapse.

**Catastrophic Collapse** An area of the floor, which must include the PC that triggered the hazard, collapses. Each creature in the area must attempt a DC 14 Reflex save:
- **Crit Success** The creature is not prone.
- **Success** The creature moves 5 feet to safe ground and is knocked prone.
- **Fail** The creature is hanging on by their fingernails; **Climb** `[one-action]` to move 5 feet to safe ground.
- **Crit Fail** The creature falls, **Damage** 1d6 P+B, and lands in the space below.
```

	
```pf2e-stats
# Yargin Balko
## Creature 1
---
==unique== ==medium== ==humanoid== ==human==

**Perception** +6

**Languages** Common

**Skills** Acrobatics +6, Athletics +5, Arcana +3, Crafting +8, Intimidation +4

**Str** +2, **Dex** +3, **Con** +3, **Wis** +0, **Cha** +0

Items lesser acid flask (4), lesser alchemist's fire (2), minor elixir of life (2), scroll of acid burst, dagger

---

**AC** 17; **Fort** +8, **Ref** +8, **Will** +3

**HP** 20

---

Speed 25 feet

**Melee** `[one-action]` dagger +6 (agile, finesse, versatile S), **Damage** 1d6+1 P

**Ranged** `[one-action]` dagger +8 (agile, finesse, thrown 20 feet, versatile S), **Damage** 1d6+1 P

**Melee** `[one-action]` bomb +8 (range increment 30 feet, splash), **Damage** varied by bomb

**Threaten the Lambs** `[one-action]` (auditory, emotion) Yargin threatens and insults any children present. Attempt a Demoralize check on any Lambs in the Fishery present in the area. On a success, any Lambs in the Fishery in Yargin's area that have been made helpful to the PCs are instead reverted to harmful actions toward the PCs.

**Trick Scroll** `[one-action]` (manipulate) Yargin attempts to Cast from his scroll of acidic burst. Yargin attempts a DC 15 Arcana check. If successful, Yargin spends his next two actions to Cast acidic burst from his scroll.
```

```pf2e-stats
# Bloo (Guard Dog)
## Creature -1
---
==small== ==animal==

**Perception** +6; low-light vision, scent (imprecise) 30 feet

**Skills** Acrobatics +5, Athletics +4, Stealth +5, Survival +4

**Str** +1, **Dex** +2, **Con** +2, **Int** -4, **Wis** +1, **Cha** -1

---

**AC** 15; **Fort** +5, **Ref** +7, **Will** +4
**HP** 8

---

**Speed** 30 feet

**Melee** `[one-action]` jaws +6 (+1/-4), **Damage** 1d4+1 P

**Pack Attack** Bloo's strikes deal 1d4 extra damage to creatures within reach of at least two of the Bloo's allies.
```

```pf2e-stats
# Hookshanks Gruller
## Creature 1
---
==unique== ==small== ==humanoid== ==gnome==

**Perception** +6

**Languages** Common, Gnomish

**Skills** Acrobatics +6, Athletics +5, Stealth +6

**Str** +2, **Dex** +3, **Con** +2, **Int** +0, **Wis** +2, **Cha** +0

**Items** kukri, studded leather, disguise kit, key to cabinet

---

**AC** 17; **Fort** +5, **Ref** +9, **Will** +5

**HP** 21

**Nimble Dodge** `[reaction]` **Trigger** A creature targets Hookshanks with an attack and he can see the attacker; **Effect** Hookshanks deftly dodges out of the way, gaining a +2 circumstance bonus to AC against the triggering attack.

---

**Speed** 25 feet

**Melee** `[one-action]` kukri +6 (agile, finesse, trip), **Damage** 1d6+3 S

**Sneak Attack** `[free-action]` Hookshanks deals an extra 1d6 extra precision damage to flatfooted creatures.

**Surprise Attack** On the first round of combat creatures that haven't acted yet are flat-footed to Hookshanks.

**Threaten the Lambs** `[one-action]` (auditory, emotion) Hookshanks threatens and insults any children present. Attempt a Demoralize check on any Lambs in the Fishery present in the area. On a success, any Lambs in the Fishery in Yargin's area that have been made helpful to the PCs are instead reverted to harmful actions toward the PCs.
```
```pf2e-stats
# Lambs in the Fishery, Upper Workroom (A7)
## Hazard 0
---
==unique== ==complex==

**Stealth** -10 and no minimum proficiency to notice

**Description** The orphan children known as Lamm's Lambs stab with their pitcforks, daggers, and otherwise harass any intruders into the domain of Gaedren Lamm.

---

**Disable** DC 16 Diplomacy to convince the children to be helpful or quiet a room.

**AC** 13; **Fort** +4, **Ref** +4, **Will** +6; **HP** 8 per room of children; **Immunities** critical hits, precision damage, swarm mind.

---

**Routine** `[three-actions]` At the beginning of each turn the Lambs choose to be helpful or harmful to the PCs and make a pitchfork Strike on each creature in the room they have chosen to be harmful towards and roll the damage once for all targets. The Lambs always choose to be harmful unless a successful Diplomacy check has been made to convince them to be helpful. The Lambs then use Chaos in the Fishery.

**Melee** pitchfork +4, Damage 1d4+1 P

**Chaos in the Fishery** The Lambs create an effect based on their allegiance, located at any point within the hazard (even within sections that have been disabled) as long as the entire hazard has not been disabled. The DC for each effect is 14.
- **Harmful** The Lambs splash water and slime from the trough over the floor, coating 4 contiguous 5-foot squares with eht effect of grease.
- **Helpful** A Lamb hurls a pitchfork with surprising accuracy at the face of any creatures considered and enemy to the PCs. If Hookshanks is present this ability always targets him. The target creature gains the blinded condition for 1 round.
```
```pf2e-stats
# Giggles
## Creature 1
---
==unique== ==medium== ==humanoid== ==human== ==orc==

**Perception** +6; Darkvision

**Skills** Acrobatics +4, Athletics +7, Intimidation +4, Survival +4

**Str** +4, **Dex** +2, **Con** +3, **Int** -1, **Wis** +1, **Cha** +0

**Items** chainmail, flail, crossbow (10 bolts)

---

**AC** 18; **Fort** +8, **Ref** +7, **Will** +4

**HP** 23

**Speed** 25 feet

**Attack of Opportunity** `[reaction]`

**Ferocity** `[reaction]`

---

**Melee** `[one-action]` flail +7 (disarm, sweet, trip), **Damage** 1d6+5 B

**Ranged** `[one-action]` crossbow +5 (range increment 120 feet, reload 1), **Damage** 1d8 P

**Bludgeoner** Giggles doesn't take the normal penalty for making a nonlethal attack when attacking with his flail.

**Threaten the Lambs** `[one-action]` (auditory, emotion) Hookshanks threatens and insults any children present. Attempt a Demoralize check on any Lambs in the Fishery present in the area. On a success, any Lambs in the Fishery in Yargin's area that have been made helpful to the PCs are instead reverted to harmful actions toward the PCs.
```

```pf2e-stats
# Lambs in the Fishery, Fishery Floor (A8)
## Hazard 0
---
==unique== ==complex==

**Stealth** -10 and no minimum proficiency to notice

**Description** The orphan children known as Lamm's Lambs stab with their pitcforks, daggers, and otherwise harass any intruders into the domain of Gaedren Lamm.

---

**Disable** DC 16 Diplomacy to convince the children to be helpful or quiet a room.

**AC** 13; **Fort** +4, **Ref** +4, **Will** +6; **HP** 8 per room of children; **Immunities** critical hits, precision damage, swarm mind.

---

**Routine** `[three-actions]` At the beginning of each turn the Lambs choose to be helpful or harmful to the PCs and make a pitchfork Strike on each creature in the room they have chosen to be harmful towards and roll the damage once for all targets. The Lambs always choose to be harmful unless a successful Diplomacy check has been made to convince them to be helpful. The Lambs then use Chaos in the Fishery.

**Melee** pitchfork +4, Damage 1d4+1 P

**Chaos in the Fishery** The Lambs create an effect based on their allegiance, located at any point within the hazard (even within sections that have been disabled) as long as the entire hazard has not been disabled. The DC for each effect is 14.
- **Harmful** The Lambs choose a PC target in the area and drop foul river water on them. The target must succeed on a Fortitude save or become sickened 1.
- **Helpful** The Lambs choose a target not allied with the PCs in the area and use their brooms to Trip the target with a +6 modifier. If Giggles is present in the area, this effect always targets him.
```

```pf2e-stats
# Drain Spider
## Creature -1
---
==tiny== ==animal==

**Perception** +5; Darkvision, web sense

**Skills** Acrobatics +3, Stealth +5

**Str** +0, **Dex** +3, **Con** +1, **Int** -5, **Wis** +0, **Cha** -4

**Web Sense** The drain spider has imprecise tremorsense to detect the vibrations of creatures touching its web.

---

**AC** 15; **Fort** +5, **Ref** +7, **Will** +3

**HP** 8

**Speed** 25 feet, climb 25 feet

---

**Melee** `[one-action]` fangs +5 (finesse), **Damage** 1d4 P plus drain spider venom

**Ranged** `[one-action]` web +7 (range, increment 10 feet), **Damage** web trap plus drain spider venom

**Drain Spider Venom** (poison); **Saving Throw** DC 15 Fortitude; **Maximum Duration** 4 rounds; **Stage 1** fatigued (1 round); **Stage 2** 1d6 poison damage plus fatigued (1 round)

**Web Trap** A creature hit by the drain spider's web attack is immobilized and stuck to the nearest surface until it Escapes (DC 15).
```
```pf2e-stats
# Gaedren Lamm
## Creature 2
---
==unqiue== ==medium== ==humanoid== ==human==

**Languages** Common

**Skills** Acrobatics +9, Athletics +8, Intimidation +5, Stealth +9, Thievery +9

**Str** +3, **Dec** +4, **Con** +1, **Int** +0, **Wis** +1, **Cha** +0

**Limping Gait** The most significant manifestation of Gaedren's long life of crime is his limp; an old wound to his left leg that reduces his speed to 15 feet.

**Items** +1 key-bladed dagger, +1 hand crossbow (20 bolts), studded leather, brass key, rusty iron key

---

**AC** 19; **Fort** +6, **Ref** +11, **Will** +9

**HP** 38

**Deny Advantage** Gaedren isn't flat footed to creatures of 2nd level or lower that are hidden, undetected, flanking, or using surprise attack.

**Nimble Dodge** `[reaction]` Trigger A creature targets Gaedren with an attack and he can see the attacker; Effect Gaedren deftly dodges out of the way, gaining a +2 circumstance bonus to AC against the triggering attack.

---

**Speed** 15 feet

**Melee** `[one-action]` dagger +11 (agile, finesse, versatile S), **Damage** 1d6+4 P

**Ranged** `[one-action]` dagger +11 (Agile, fineese, thrown 20 feet, versatile S), **Damage** 1d6+4 P

**Ranged** `[one-action]` hand crossbow +11 (range increment 60 feet, reload 1), **Damage** 1d8 P

**Abusive Inspiration** `[two-actions]` (attack, auditory, emotion, mental) Gaedren threatens and attempts a hand crossbow Strike against Gobblegut. If successful, Gobblegut becomes frenzied and gains a +1 to attack rolls, damage rolls, and takes a -1 penalty to AC, saves, and skill checks until the start of Gaedren's next turn.

**Sneak Attack** Gaedren deals 1d6 extra precision damage to flat-footed creatures.

**Surprise Attack** On the first round of combat, creatures that haven't yet acted yet are flat-footed to Gaedren.

**Your Next!** `[reaction]` (emotion, fear, mental); **Trigger** Gaedren reduces a creature to 0 Hit Points; **Effect** Gaedren attempts an Intimidation check with a +2 circumstance bonus to Demoralize a single creature he can see and that can see him.
```
```pf2e-stats
# Gobbleguts (Crocodile)
## Creature 2
---
==large== ==animal==

**Perception** +7; low-light vision

**Skills** Athletics +8, Stealth +7 (+11 in water)

**Str** +4, **Dex** +1, **Con** +3, **Int** -5, **Wis** +1, **Cha** -4

**Deep Breath** Gobbleguts can hold its breath for about 2 hours.

---

**AC** 17; **Fort** +9, **Ref** +7, **Will** +5

**HP** 30

---

**Speed** 20 feet, swim 25 feet

**Melee** `[one-action]` jaws +10 (+5/+0), **Damage** 1d10+4 P plus Grab

**Melee** `[one-action]` tail +10 (+5/+0) (agile), **Damage** 1d6+4 B

**Aquatic Ambush** `[one-action]` 35 feet

**Death Roll** `[one-action]` (attack) **Requirements** Gobbleguts must have a creature grabbed; **Effect** Gobbleguts tucks its legs and rolls rapidly, twisting its victim. It makes a jaws Strike with a +2 circumstance bonus to the attack roll against the grabbed creature. If it hits, it also knocks the creature prone. If it fails, it releases the creature.
```
