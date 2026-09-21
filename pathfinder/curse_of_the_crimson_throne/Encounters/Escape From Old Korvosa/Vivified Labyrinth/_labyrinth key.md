![[pathfinder/curse_of_the_crimson_throne/Encounters/Escape From Old Korvosa/Vivified Labyrinth/map.png]]

# E1. Dungeon Entrance
> The tunnel curves sharply north here, ending at a set of large bronze doors, each carved with images of tigers chasing other tigers in four adjacent circles. At the center of each circle of tigers, a snarling tiger head looks out.

**illusory object** (seek DC 26) The east bend is an illusion concealing stairs that descend to area E21.

# E2. Labyrinth Entrance
> Two statues, each depicting a tiger-headed man, stand in alcoves to either side of the doors. Their arms are wide, as if to usher visitors forward into the room beyond.

**gap in the floor, walls, and ceiling** (seek DC 15).

Both statues depict Bahor is his true form.

# E3. First Lever
> Two alcoves open on either side of this otherwise empty room. In one alcove, a long lever with an ebony handle protrudes from the wall.

Lever triggers a partial rotation.

# E4. Corrupted Pool
> A five-foot-diameter pool of crystal clear water nearly fills this small, circular room.

```pf2e-stats
# Corrupted Pool
## Hazard 7

---
==mechanical== ==trap==

**Stealth** DC 23 (expert) to notice the scent of chemicals

**Complexity** Simple

**Description** A five-foot-diameter pool of crystal-clear water that is infused with with a colorless, tasteless, and nearly odorless Vudrani scorpion venom.

---

**Disable** Crafting DC 25 to introduce reagents to nullify the water's poison.

**AC** 25; **Fort** +15; **Ref** +14 

**Hardness** 14; **HP** 56 (BT 28); **Immunities** acid, critical hits, object immunities, precision damage

**Envenomed Water** `[reaction]` **Trigger** A creature drinks from the pool. **Effect** The creature must attempt a Fortutude save against the effect of Vudrani Scorpion Venom.

---

**Vudrani Scorpion Venom** (poison) **Saving Throw** DC 25 Fortitude; **Max Duration** 6 rounds; **Stage 1** 1d10 poison damage and enfeebled 1 (1 round); **Stage 2** 2d10 poison damage and enfeebled 2 (1 round); **Stage 3** (1 round) 2d10 poison damage and enfeebled 3 (1 round).
```

# E5. Refreshing Pool
> A five-foot-diameter pool of murky green water nearly fills this small, circular room.

Once per day, any creature that drinks from the pool regains 4d8+10 HP.

**Search** Anyone searching the room or attempting to drink from the pool will inevitably see the symbol.
```pf2e-stats
# Symbol of Fear
## Hazard 7

---
==magical== ==trap==

**Stealth** DC 22 (trained, Arcana, Religion, Occultism)

**Complexity** Simple

**Description** A magical symbol meaning fear -or- facing one's fear is etched on the wall.

---

**Disable** Thievery DC 27 (expert) to chip away at the symbol while Averting your Gaze, or Dispel Magic (rank 3; DC 29) to counteract the symbol.

**Terrorize the Righteous** `[reaction]` (emotion, magic, fear, mental); **Trigger** a creature without the unholy trait looks at the symbol; **Effect** The creature must succeed at DC 29 Will save or be subjected to the effects of a Fear spell.

---

**Reset** The symbol automatically resets after 1 minute.

```
# E6. Hall of Pain
Sivit has placed a symbol of pain on the floor here.
```pf2e-stats
# Symbol of Pain
## Hazard 7

---
==magical== ==trap==

**Stealth** DC 22 (trained, Arcana, Religion, Occultism)

**Complexity** Simple

**Description** A magical symbol meaning fear -or- facing one's fear is etched on the wall.

---

**Disable** Thievery DC 27 (expert) to chip away at the symbol while Averting your Gaze, or Dispel Magic (rank 3; DC 29) to counteract the symbol.

**Torment the Righteous** `[reaction]` (emotion, magic, fear, mental); **Trigger** a creature without the unholy trait looks at the symbol; **Effect** The creature must succeed at DC 29 Will save or be subjected to the effects of a Phantom Pain spell heightened to rank 3.

---

**Reset** The symbol automatically resets after 1 minute.
```
# E7. Three Flavors of Venom
> Three large wooden chests, their lids decorated with carvings of cavorting tigers, sit against one wall of this room. Some sort of message seems to be carved on each lid. Colorful frescoes on the wall opposite the chests depict hundreds of tigers marching in widening circles around a single green gem the size of a fist, set in the wall and carved to resemble a tiger’s head.

Inscriptions (left) *By gentle caress shall truth be known* (middle) *Life within but Death without* (right) *Breathe deep your salvation*

```pf2e-stats
# Chest on the Left
## Hazard 7

---

==mechanical== ==trap==

Stealth DC 27 (expert) to notice the dried poison flakes on the wood.

Complexity Simple

Description On ornate chest bearing the engraving, "By gentle caress shal truth be known" and coated with terniav poison.

---

Disable Thievery DC 26 to wipe the poison away.

**AC** 25; **Fort** +0; **Ref** +0

**Hardness** 0; **HP** 1; **Immunities** critical hits, object immunities, precision damage

**Poisoned Chest** `[reaction]` **Trigger** A creature touches the chest; **Effect** The creature must attempt a Fortitude save against the effects of terinav root poison.

---

**Terinav Root Poison** (contact, poison) **Saving Throw** DC 30 Fortitude; **Onset** 1 minute; **Max Duration** 6 minutes; **Stage 1** clumsy 1 and 5-foot status penalty to all speeds (1 minute); **Stage 2** clumsy 2 and 10-foot status penalty to all speeds (1 minute); **Stage 3** clumsy 3 and 15-foot status penalty to all speeds.

```
The middle chest contains several potions and a coiled [Blood Cobra](https://2e.aonprd.com/Monsters.aspx?ID=3202)
- 3x Healing Potion (moderate)
- 3x Elixir of Life (moderate)
```pf2e-stats
# Chest on the Right
## Hazard 7

---

==mechanical== ==trap==

**Stealth** DC 27 (expert) to notice fumes seeping out when cracked open.

**Complexity** Simple

**Description** A chest with the engraving, "Breath deep your salvation" and filled with Brain Fog.

---

**Disable** Thievery DC 26 to filter the mist with cloth and water.

**AC** 25; **Fort** +0; **Ref** +0

**Hardness** 0; **HP** 1; **Immunities** critical hits, object immunities, precision damage

**Mist Release** `[reaction]` **Trigger** The chest is opened; **Effect** All creatures within 30 feet of the chest must attempt a Fortitude save against the effects of Brain Fog.

---

**Brain Fog** (inhaled, poison) **Saving Throw** DC 25 Fortitude; b 1 hour; **Stage 1** enfeebled 1 and stupefied 1 (1 minute); **Stage 2** enfeebled 2 and stupefied 2 (10 minutes); **Stage 3** fatigued, enfeebled 4 and stupefied 4 (1 hour)
```
# E8. Second Lever
Pulling the lever triggers a partial rotation.

# E9. The Biting Tigers
> Both walls of this twenty-foot-long corridor are decorated with row upon row of tiger heads. Each head appears to be that of an actual, once-living tiger. The heads are remarkably well-preserved—their gaping mouths and glaring eyes even appear to be moist.

**Searching** DC 29 to notice the bypass switch at the entrance.
```pf2e-stats
# Biting Tigers
## Hazard 10

---
==complex== ==mechanical== ==trap==

**Stealth** +19 (expert)

**Description** The tiger heads on the walls animate and visciously attack anyone within reach.

---

**Disable** Theivery DC 25 to disconnect one of the tiger heads within reach from the wall. or Perception 29 to notice the bypass switch at the entrance to the room.

**AC** 29; **Fort** +22; **Ref** +14; (each head)

**Hardness** 10; **HP** 50 (BT 25); **Immunities** critical hits, object immunities, precision damage

**Viscious Bite** `[reaction]` **Trigger** 1 round after the firsst creature enters the room; **Effect** Each tiger makes a bite Strike against a creature within reach, then the trap rolls initiative.

---

**Routine** `[three-actions]` The trap uses each action to make a bite Strike against a creature within reach. Only one bite may be used per tiger head, to a maximum of three heads each round.

**Melee** `[one-action]` bite +26 **Damage** 2d12+14 piercing plus 1d6 persistent bleed damage on a critical hit.

---

**Reset** The trap deactivates and resets if no creatures are present in the room. If the bypass switch is flipped, the trap deactivates and resets in 3 rounds.
```
**Searching** DC 25 to find the secret door at the end of hall leading to area E10.

# E10. The Fangs of Diomazul
> A ten-foot-wide, two-foot-tall well rises from the center of this circular room. Inky water fills the well nearly to its rim, obscuring its depths. A stone statue of a rearing snake rises from the center of the well. Along the length of the serpent’s body, dozens of carved arms cross of the creature’s belly—each arm grips a long curved blade. The statue’s serpentine head rises ten feet above the surface of the water, gazing down coolly to the northeast with amethyst eyes.

**Investigate** DC 30 Religion to recognize the obscure Vudrani deity, Diomazul, The Serpent of Eighty Blades—a god noted for its ferocity and cruelty in battle.

```pf2e-stats
# Fangs of Diomazul
## Hazard 10

---
==complex== ==mechanical== ==trap==

**Stealth** +19 (expert) to notice the mechinewerks beneath the surface of the water.

**Description** Curved blades spring out from the base of the well and spin furiously around the room, striking anyone on the ground near the well.

---

**Disable** Thievery DC 31 (expert) to jam the blades or Perception DC 29 to notice the bypass switch at the entrance of the room.

**AC** 30; **Fort** +22; **Ref** +16

**Hardness** 19; **HP** 72 (BT 36); **Immunities** critical hits, object immunites, precision damage

**Spin Blades** `[reaction]` **Trigger** 1 round after a creature enters the room; **Effect** The trap makes a whirling blade Strike against any creature standing on the ground within 5 feet of the well, then the trap rolls initiative. While the trap is activated, all squares within 5 geet of the base of the well are treated as difficult terrain.

---

**Routine** On it's turn each round, the trap's blades spin, making whirling blade Strikes against any creature standing on the ground within 5 feet of the well.

**Melee** whirling blade +25 **Damage** 2d12+13 slashing plus 1d6 persistent bleed and -10 move speed on a critical success.

---

**Reset** The trap deactivates and reset when there are no creatures left in the room. When the bypass switch is flipped, the trap deactivates for 3 rounds, and then automatically resets.
```
**Treasure** The statue’s eyes can be pried out of the statue and are worth 50 gp each. Once they are removed, the trap can no longer be triggered.

**Search** DC 25 to find the secret door to area E9.

# E11. The Wailing Maidens
> Eight alcoves line this long, narrow hallway. Inside each alcove stands a human-sized, upright iron casket, the image of a sobbing woman decorating its lid. The hallways’ floor gleams bright red, a mosaic of tiny red stones giving the appearance that the hall is awash in blood.

**Search** DC 29 to notice the bypass switch at the entrance.

```pf2e-stats
# Wailing Maidens
## Hazard 10

---
==complex== ==mechanical== ==trap==

**Stealth** +19 (expert) to notice the pressure plates beneath the jeweled mosaics.

**Description** A cruel trap that lifts the floor into slopes to slide intruders in front of iron maidens that stun and stab with deadly spikes.

---

**Disable** Thievery DC 31 (expert) to immobilize the lifting floor plates or Perception DC 29 to notice the bypass switch at the entrance of the hall.

**Slide, Scream, Skewer** `[reaction]` **Trigger** 2 rounds after a creature enters the room; **Effect** Each square in the room not flanked by an iron maiden rises up in a 45 degree angle facing south. Any creature caught in an affected square must succeed against a DC 22 Reflex save or be moved into the adjacent square to the south. This effect is forced movement. Then immediately after, each iron maiden on the western wall uses maiden's scream and the trap rolls for initiative.

---

**Routine** On the trap's turn each round, the iron maidens along the walls open to reveal an interior lined with spikes. The spikes extend on poles, making a spike skewer Strike against any creature standing in an adjacent square. The spikes then retract into their respective iron maidens.

**Melee** spike skewer +26 Damage 2d10+13 piercing

**Maiden's Scream** (auditory, incapacitation, sonic) A defeaning shriek emits from each iron maiden along the walls. Any creature adjacent to an iron maiden must attempt a DC 24 Fortititude save.
	**Critical Success** The creature is deafened for 1 round.
	**Success** The creature is stunned 1 and deafened for 1 round.
	**Failure** The creature is stunned 2 for 1 round and defeaned for 1 minute.
	**Critical Failure** The creature is stunned 3 for 1 round and defeaned for 1 minute.

---

**Reset** The trap deactivates and reset after it has repeated its routine for 4 rounds. The trap takes 1 minute after this to fully reset, filling the room with ominous clicking and grinding. The trap also deactivates and starts to reset once the bypass switch is flipped.
```
# E12. Stinging Wasps
> The walls, floor, and ceiling of this chamber are decorated with a complex mosaic depicting an immense swarm of angry wasps.

**Search** DC 29 to notice the bypass switch at the entrance.

```pf2e-stats
# Stinging Wasps
## Hazard 10

---
==complex== ==mechanical== ==trap==

**Stealth** +19 (expert) to notice tiny needle-sized holes in the floor, walls, and ceiling.

**Description** Thousands of 6-inch-long needles stab out of the walls, floor, and ceiling of this room in waves, creating a beautiful rippling effect.

---

**Disable** Thievery DC 31 (expert) to jam enough needle holes to prevent the wave from continuing or Perception DC 29 to notice the bypass switch at the entrance.

**Needle Wave** `[reaction]` **Trigger** 1 round after a creature enters the room; **Effect** A wave of needles ripples along the room. The trap makes a numbing needle Strike against any creature standing in this room or climbing its walls, then rolls for initiative. While this trap is active, this room is considered to be difficult terrain.

---

**Routine** On the trap's turn each round, the wave continues around the room and the trap makes a numbing needle Strike against any creature standing in this room or climbing its walls.

**Melee** numbing needle +28 **Damage** 1d8+13 piercing plus giant wasp venom

**Giant Wasp Venom** (poison) Saving Throw DC 25 Fortitude; Max Duration 6 rounds; Stage 1 2d6 poison damage and clumsy 1 (1 round); Stage 2 3d6 poison damage and clumsy 2 (1 round); Stage 3 4d6 poison damage and clumsy 2 (1 round);

---

**Reset** The trap deactivates and resets when there are no creatures standing in this room. When the bypass switch is flipped, the trap deactivates for 3 rounds and then automatically resets.
```
# E13. Meditation Chamber
> A six-inch-tall bronze dais on the floor in the muddle of this otherwise empty room supports a polished column of black marble. The black stone seems to be vibrating softly, filling the air with a faint hum.

**Creatures** [[Vimanda]] starts here when the players begins their exploration of the labyrinth.
```pf2e-stats
# Sonorous Stone
## Item 15

---
==rare== ==artifact== ==emotion== ==healing== ==mental== ==occult==

Bulk 40

---

A polished column of black marble. The stone seems to be vibrating softly, filling the air with a faint hum. Any creature that spends 1 minute within 5 feet of an active sonorous stone receives the benefits of a calm emotions spell.
In addition, a creature that touches an active sonorous stone is targeted by a restoration spell that also allows it to recall up to 3 expended spell slots - the spells are prepared again or spell slots are once again available, just as if they had never been used. A sonorous stone can be activated 4 times per month, after which it becomes dormant for 1 month while it rebuilds its charge.
```

# E14. Hidden Lever
> The floor of this empty room is strewn with bones and patches of mold.

**Search** DC 30 to discover the secret door to the alcove with another lever. The lever trigger a partial rotation of the labyrinth.

# E15. Threatening Murals
> The walls of this oddly shaped hallway are decorated in a complex mural depicting a hot, steaming jungle brimming with hungry life. Predators of every sort stalk and maim and feed on dozens of hapless people. In the canopy above, monkeys, snakes, and birds seems to chatter and mock the victims below.

**Investigate** Those who examine these murals swiftly find themselves among the victims represented. This relatively minor illusion has no further effect.

# E16. Transport Room
> Four alcoves in the walls of this room contain floating spheres of mist, each hovering three feet off the ground. Each sphere is one foot in diameter and of a different color—black, white, green, and gold. Just north of the strange floating spheres, two lever protrude from opposite walls.

**East Lever** Triggers a partial rotation of the labyrinth.

**West Lever** When up allows the spheres to act as teleporters as described below. When down (current), the spheres teleport to a random unoccupied cell in area E21.

**White Sphere** Teleports anyone who touches it to area [[#E2. Labyrinth Entrance]].

**Black Sphere** Teleports anyone who touches it to area [[#E13. Meditation Chamber]].

**Green Sphere** Teleports anyone who touches it to area [[#E20. Sivit’s Throne]].

**Gold Sphere** Teleports anyone who touches it to area [[#E5. Refreshing Pool]].

# E17. Disposal Room
> The filthy floor of this chamber is covered by a thick layer of rubble, bones, and other debris. A lever protrudes from the center of the wall opposite the entrance.

**Lever** triggers a partial rotation of the labyrinth.

**Investigate** After victims succumb to the Vivified Labyrinth, Sivit generally diposes of the bodies in this room. Some time later, the remains are carried away by the Arkonas, typically for meals. There’s currently nothing of interest for the players in this chamber.

# E18. Hall of Slumber
> A short hallway leads out of this small room.

**Trap** Sivit has placed a symbol of sleep on the floor of this room.

```pf2e-stats
# Symbol of Sleep
## Hazard 7

---

==magical== ==trap==

**Stealth** DC 22 (trained in Arcana or Occultism)

**Description** A symbol of sleep is imbued into the floor of this room.

---

**Disable** Thievery DC 27 (expert) to chip away at the symbol while Averting your Gaze, or Dispel Magic (rank 3; DC 29) to counteract the symbol.

**Subdue the Righteous** `[reaction]` (incapacitation, mental, sleep); **Trigger** a creature without the unholy trait looks at the symbol; **Effect** The creature must succeed at DC 29 Will save or be subjected to the effects of a Sleep spell heightened to rank 6.

---

**Reset** The symbol automatically resets after 1 minute.
```

# E19. Hall of Stunning
> A door lies at one end of this crooked hall.

Trap Sivit has places a symbol of stunning on the floor of this room.

```pf2e-stats
# Symbol of Stunning
## Hazard 7

---

==magical== ==trap==

**Stealth** DC 22 (trained in Arcana or Occultism)

**Description** A symbol of stunning is imbued into the floor of this room.

---

**Disable** Thievery DC 27 (expert) to chip away at the symbol while Averting your Gaze, or Dispel Magic (rank 3; DC 29) to counteract the symbol.

**Stun the Righteous** `[reaction]` (incapacitation, mental); **Trigger** a creature without the unholy trait looks at the symbol; **Effect** The creature must succeed at DC 29 Will save or be subjected to the effects of a Synaptic Pulse spell.

---

**Reset** The symbol automatically resets after 1 minute.
```

# E20. Sivit’s Throne
> A great green throne sits atop a dais in the northern end of the room. To either side stand statues of a tiger-headed man—each hold aloft a pair of chains from which manacles dangle. Dried blood spatters the walls, the floor, and even the throne and statues, filling the room with its stale reek.

**Search** DC 26 to notice the key under the throne cushions.

**Creatures** [[Sivit]] usually remains in this location while her victims explore the labyrinth. Vencarlo Orsini, her last victim, is manacled to the western statue (fatigued, unconscious, wounded 1).

# E21. Torture Chamber

# E22. Torturer’s Home

# E23. The Gizzard
