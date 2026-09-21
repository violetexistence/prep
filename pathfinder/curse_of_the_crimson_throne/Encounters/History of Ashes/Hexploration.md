#### Activities
These hexploration activities differ from the ones described in the GM Core. Players are given two additional resources to manage. **Travel Points** (TP) refresh each day and allow characters to explore the hex map and discover its mysteries. **Stress** accrues from wounds and other hazards, and resets only when the characters find downtime.

**Skins Full** Add a +1 status bonus to all skill and Perception checks.
**Well Fed** Add a +1 status bonus to all saves.
**Fresh** Increase travel Speed by 5 feet.

```pf2e-stats
# Travel

---

==exploration== ==group== ==move==

Your group gains 1 Travel Point (TP) for each 5 feet of its travel speed. Travel speed is equal to the walking speed of its slowest member. Spend travel points to enter a new hex.

| Entering Hex | Cost (TP) |
| ---- | :----: |
| normal terrain | 2 |
| difficult terrain | 3 |
| greater difficult terrain | 4 |
| usable trails | -1 |

**Hustling** By moving quickly, taking fewer breaks, and pushing longer, your group doubles its travel Speed. However, at the end of the march, each member of the group takes 2 Stress (basic Fortitude save). Push an additional terrain and creature onto the Wandering Monster table.

```
```pf2e-stats
# Navigate

---

==concentrate== ==exploration== ==move==

Attempt a Survival check against the Zone DC. Only one check can be made to navigate in the same hex per day. Once you have entered a new hex, a new check can be made to discover a new trail.
**Critical Success** As success, but clear the lost condition.
**Success** You find a usable trail in the direction of your group's travel. Reduce lost by 1.
**Failure** +1 lost
**Critical Failure** +2 lost

---
**Trails** When you follow a trail into a new hex, roll 1d6 to determine where the trails leads.
**4-6** Maintain course
**3** Veer right
**2** Veer left
**1** Trails ends

**Lost** This condition always includes a value. **Trigger** Enter a new hex while lost; **Effect** The GM secretly rolls a number of d6 equal to the condition value, using the lowest result from *Trails* to determine your actual course. A 1 indicates you remain in the current hex.
```
```pf2e-stats
# Search

---
==exploration== ==move== ==secret==

---
You travel at half Speed, instead spending time exploring hexes you enter, looking for unusual features or specific sites. You automatically find any special feature that doesn't require a check to find, and you attempt the appropriate checks to find hidden special features. Push terrain off the Wandering Monster table.

---
**Expeditious Search** Travel at full Speed while searching.
**Thorough Search** You cannot fail to find hidden features unless you critically fail.
```
```pf2e-stats
# Scout

---
==exploration== ==move==
**Requirements** Your group is not hustling.

---
You range up to an hour ahead, surveying terrain, looking for danger, and regrouping throughout the day to confer with your group's navigator. When you enter a new hex, also reveal the three forward hexes in the direction of your group's travel.
At the start of any encounter, members of your group gain a +1 circumstance bonus to their initiative rolls. 
Scouting is hard work. When you finish travel for the day, mark 2 Stress (basic Fortitude save).
As part of scouting, you can keep an eye out for likely campsites. At any point during travel, select a hex you have scouted and attempt a Perception check against the Zone DC.

**Critical Success** As success, but add +2 to the first campsite roll. If you're a master with Perception, the bonus is +3, and if you're legendary, it's +4.
**Success** Roll on the campsite table with a +1. You can use this campsite or roll again with no modifier. You must use the second result.
**Failure** As success, but you do not get a second roll.
**Critical Failure** As failure, plus Wandering Monster.

---
**Scout Dedication** If you have this archetype, reduce stress taken by -1.
```
```pf2e-stats
# Cover Tracks

---
==concentrate== ==exploration== ==move==

Push creatures off the Wandering Monster table for today. 

---
**Trackless Journey** You can perform another exploration activity while covering tracks.
```
```pf2e-stats
# Subsist

---
==exploration== ==move==

You attempt a Survival check against the Zone DC to procure subsistence. The normal -5 circumstance penalty applies, if you undertake this activity while traveling. Otherwise, this activity gains the ==camping== trait.

**Critical Success** As success, plus one more person does not mark Stress.
**Success** If your group is out of usable provisions, you do not mark Stress today. Find 1d4 special ingredients.
**Failure** Find 1d4 special ingredients.
**Critical Failure** Roll a Wandering Monster.
```
```pf2e-stats
# Team Up

---
==exploration==

Choose another member of the group and describe how you are going to help them. When they are about to make a check, you attempt a skill decided by the GM. The typical DC is 15, but the GM might adjust this DC for particularly hard or easy tasks. This activity can be performed in camp.

**Critical Success** They take a +2 circumstance bonus to the triggering check. If you're a master with the check you attempted, the bonus is +3, and if you're legendary, it's +4.
**Success** They take a +1 circumstance bonus to the triggering check.
**Critical Failure** They take a -1 circumstance penalty to the triggering check.
```
```pf2e-stats
# Track

---
==concentrate== ==exploration== ==move==

You follow tracks, moving at half your travel Speed. After a successful Survival check, you can continue following the tracks at half your Speed attempting a check each time you enter a new hex.
Following the tracks of your quarry is its own form of navigation. If your quarry is following a trail, you also have a trail.

**Critical Success** As success, plus gain some insight on your quarry.
**Success** Still following
**Failure** Lost the quarry, 1 TP to try again today
**Critical Failure** Lost the quarry, cannot try again today

---
**Experienced Tracker** If you have this ability, you can take a -5 penalty to your tracking check instead of moving at half Speed and if you're a master in Survival, you don't take the -5 penalty. If you're legendary in Survival, you no longer need to roll a new Survival check when entering a new hex, though you still need to roll whenever the terrain type of the new hex is significantly different.

**Swift Tracker** If you have this ability, you move at your full travel Speed. If you're a master, you only roll your Survival check again if the terrain changes. If you're legendary in Survival, you can perform another exploration activity while tracking.
	If you roll Survival for initiative while tracking your hunted prey, when you start your first turn of the encounter, you can Stride toward your quarry as a free action.
```

| 1d20  | Wandering Monster |
| ----- | ----------------- |
| 1     | Roll Twice        |
| 2-5   | Creature          |
| 6-8   | Terrain           |
| 9-10  | Weather           |
| 11-12 | Supplies          |
| 13-14 | Equipment         |
| 15+   | No Monster        |

| 2d6  | Campsite |
| ---- | -------- |
| 2-5  | Risky    |
| 6-8  | Normal   |
| 9-12 | +Amenity |
#### Campsites
**Normal** After a day of hexploration, characters are tired (-Fresh), hungry (-Well Fed), and have drunk their water (-Skins Full). The GM make a secret Wandering Monster check at the beginning of camp. Monsters rolled can turn up at any time during camp. 

In addition to the time spent resting, taking turns on watch, and taking care of themselves personally, each character can choose a camping activity. One these all activities are resolved, if the campsite survives the night, the characters wake rested and may perform their daily preparations before continuing hexploration.

If a character has full skins, is well fed, does not have any Stress marked, they also mark Fresh.

**Risky** As normal, plus once all camping activities are finished, attempt a DC 5 flat check. On a failure, whatever risk is posed at this campsite befalls your group. As a result, all members of your group mark 2 Stress and cannot start the fresh the next day.

#### Amenities
**Shelter** A campsite with shelter pushes weather off the Wandering Monster table.
**Water** Availability of fresh water at your campsite allows your group to refill their skins and gives cooks a +1 circumstance bonus to their checks.
**Concealment** A campsite hidden from view pushes creatures off the Wandering Monster table.

#### Provisions
If all provisions are used, all group members mark 1 Stress. Character can attempt to subsist in order to avoid marking Stress.
```pf2e-stats
# Repair Project

---
==camping== ==safety==

Choose a number of damaged (but not destroyed) items which combined total up to your level. Make one check to repair all of them.
**Critical Success** As success, but you finish the project quickly and can take another camping action.
**Success** You restore them to full Hit Points.
**Failure** You restore 5 Hit Points to the item, plus an additional 5 per proficiency rank you have in Crafting (for a total of 10 HP if you are trained, 15 HP if you're an expert, 20 HP if you're a master, or 25 HP if you're legendary).
**Critical Failure** You deal 2d6 damage to one of the items. Apply the item's Hardness to this damage. Apply the failure result instead to any other items.
```

```pf2e-stats
# Craft Consumables

---
==camping== ==safety==

You can craft consumables while in camp, assuming you meet the requirements. Each camping activity spent crafting counts as a day of work.
```
```pf2e-stats
# Cook

---
==camping==
**Requirements** cookware, usable provisions

---
Once the party finishes all camping activities, announce your DC and describe the meal you prepared. Attempt a Cooking Lore check to see how many bites go in the pot. Dish out as many bites as you want to everyone's plate, plus a bonus bite to anyone that yummed your description.
**Critical Success** Double your pot dice and the first character to get well fed by this meal discovers a new favorite ingredient.
**Failure** The pot has yuck 1.
**Critical Failure** The pot has yuck 2.

| Cooking | DC | Success Bites | Critical Bites |
| :--- | :--: | :--: | :--: |
| Trained | 15 | 2d8 | 4d8 |
| Expert\* | 20 | 2d8+10 | 4d8+10 |
| Master\* | 25 | 2d8+20 | 4d8+20 |
| Legendary\* | 30 | 2d8+30 | 4d8+30 |
| \*Increased difficulty is optional |||

---
**Scraps** Any bites left in the pot after everyone is finished can be reused the next day. Before attempting a Cooking check, decide whether to keep the scraps in the pot as additional bites in the new meal or discard them. A pot cannot have a lower yuck value than any scraps in it.

**Manage Provisions** You can mark 1 Stress to also manage provisions as part of cooking.
```
```pf2e-stats
# Enjoy a Meal

---
==camping==

Take a number of bites off your plate and roll 1d6 for each bite. You can also take bites from someone else's plate, but you might want to ask them first! Evaluate each die using the results below. If the meal includes any of your favorite ingredients, add 1 to each die.
**6+** Well Fed! You can throw this die away along with any other die.
**4-5** You can keep going
**1-3** If this result is equal to or less than the yuck in the pot, you are sickened 1 until you complete your next daily preparations. Otherwise, you can keep going.

---
**Yum** If you yummed the meal when it was described by the cook, you must take at least one bite.

**Yuck** If you did not yum, the yuck in the pot is +1 for you.

**Stuffed** If you roll more than one 6, you take a -1 status penalty to Perception checks and Reflex saving throws until after you have rested.
```
```pf2e-stats
# Manage Provisions

---
==camping==

You spend time tracking usage of consumables, ensuring supplies are properly stowed, and ensuring equipment is functioning properly. Attempt a Survival or Accounting Lore check. Consult the table below to find the right DC.

**Critical Success** Push supplies and equipment off the Wandering Monster table for the next day.
**Success** Push supplies off the Wandering Monster table for the next day.

| Expedition | DC |
| ---- | :----: |
| Up to 1 week | 15 |
| Up to 1 month | 20 |
| Up to 6 months  | 25 |
| Years | 30 |
```
```pf2e-stats
# Extra Rest

---
==camping==

After you have rested, clear 1 Stress.
```
```pf2e-stats
# Fortify Camp

---
==camping==

You spend time making improvements to your campsite. Attempt a DC 20 (1 amenity), DC 25 (2 amenities), or DC 30 (3 amenities) Crafting or Warfare Lore check. Allies gain a +1 circumstance bonus to initiative rolls and Perception checks to Seek creatures attempting to sneak up on the camp. If you are a master in your skill, this bonus is +2.

**Critical Success** Your fortifications are permanent.
**Success** Your fortifications last for up to seven days.
**Failure** Your fortifications last until the next day.
**Critical Failure** As failure, plus Wandering Monster.
```
```pf2e-stats
# Study

---

==camping== ==concentrate== ==secret==

Choose a subject on which you have related material, such as a scholarly journal, or perhaps the subject itself. You make up to 6 recall knowledge checks about the subject.
```
```pf2e-stats
# Update Map

---

==camping== ==concentrate== ==safety==

**Requirements** cartographer's kit
**Skill** Crafting (expert) or Cartographic Lore (trained)

---

Add up to 8 explored or reconnoitered hexes to your map, plus up to 8 more hexes for each additional level of proficiency. Traveling in mapped hexes does not require a successful navigate check to rediscover trails.

---
**Impeccable Crafting** If you have this ability, you update your map in addition to another exploration activity.

**Spontaneous Cartography** Casting this spell adds your current hex to your map. When cast at 6th level, it adds each adjacent hex as well.
```
```pf2e-stats
# Have a Conversation

---
==camping==
**Requirements** You have at least one hero point

Take a quiet moment and ask another character for something you need. Your character articulates it in concrete terms, but you as a player should understand the actual underlying emotional need as well. 
If they give it to you, give them one of your hero points. If they have at least one hero point, they can refuse and give you one of their hero points instead.
```

#### Group
These are activities undertaken by all members of your group. Its outcomes apply to each
member of the group. A group’s travel speed is equal to the movement speed of its slowest member. Splitting into multiple groups may allow characters with higher movement speeds to scout or reconnoiter more hexes. 

#### Stress
Each character has a stress tracker. It begins at zero (0) and resets to zero (0) after 24 hours of downtime in a safe haven. There is no player-driven way to reduce stress while traveling in the wilderness, although the GM may provide special opportunities to do so.

**Gaining Stress**
- Hit by an attack from a simple hazard or failing a saving throw. Take +1 stress or +2 on a critical hit or critical failure result on your save.
- Taking environmental damage during hexploration, such as from severe heat or cold, weather or hazardous terrain. Take +1 stress.
- Losing the wounded condition. Take +1 stress for each wounded level lost.
- Hustling

**Applying Stress**
When you roll **initiative**, you lose Hit Points equal to your level times your current stress level. Losing these Hit Points does not count as taking damage. If this brings your current Hit Points to 0, set your current Hit Points to 1 instead.

**Exhaustion**
Once your stress level reaches **3 plus CON**, you are *fatigued*. This condition persists until your stress level is reduced below this threshold.

#### Safety
Activities with this trait require a safe campsite. Typically, a campsite with both shelter and concealment is considered safe. You can make ordinary campsites safe by _fortifying them_.

#### What food is in the desert?

***Plants***
- **Cactus** Most species are edible. Prickly Pear, Saguaro, Desert Christmas, and Cholla are best.
- **Fire Bush** (the flowers are edible, springtime only)
- **Agave** flowers and bugs are edible when boiled
- **Chia Sage** The whole plant is edible, but the seeds are especially full of energy.
- **Date Palm** The fresh fruit is edible when ripe.
- **Desert Amaranth** Eat the whole thing but look out for spines.
- **Desert Raisin** Eat when it is green-yellow in color.
- **Mesquite** The pods from these trees are edible.
- **Pinyon Pine** Eat the pine nuts.
- **Yucca** Spiky but completely edible. Better grilled.

***Animals***
- **Lizards** Cook thoroughly since they can carry salmonella. Avoid Gila monsters and beaded lizards. Tail meat tastes the best.
- **Snakes** As above but sometimes more hazardous to hunt.
- **Turtles** Good snack. Cook thoroughly.
- **Insects** Chock full of protein and fat, non-poisonous insects make for great survival food.
- **Ankhrav** If you can harvest the young of a hive without having to kill the disturbing number of adults living in it, this is a large amount of potential food.
- **Storval Aurochs** Larger and more aggressive than other breeds — hard to kill and a lot of work to process but yields a ton of usable meat and other materials.
- **Small Mammals** Tasty but scarce. Trapping is best as there is little cover for hunters.

#### Equipment

```pf2e-stats
# Dolor-P0e-d
## Item 5

---
==uncommon== ==magical== ==wand==
**Price** 160 gp
**Usage** held in 2 hands; Bulk L

---
This lightweight, durable box sporting a rainbow swatch painted on top encloses a stack of blank parchment. A collapsible spyglass runs through two sides of the box.

**Activate** Cast a Spell; **Frequency** once per day, plus overcharge; **Effect** You cast spontaneous cartography (3rd) targeting the current hex or an adjacent hex. A blank parchment is then spit out of a slot in the box front. One minute later, a map of the targeted hex appears on this page.
```
```pf2e-stats
# Scarab Dust
## Item 8

---
==uncommon== ==magical== ==consumable==
**Price** 100 gp
**Usage** held in 1 hand; **Bulk** -
**Activate** `[one-action]` (manipulate)

This dust comes in a small container such as a pill box or amulet. When opened the dust soars into the air where it becomes a swarm of flying green scarab beetles that seek (immediate) or search (1 minute) on your behalf. Any secret checks use your Perception with a +2 circumstance bonus and if you succeed, you get a critical success instead.

---
**Hexploration** Scarab Dust can be consumed to grant your Search activity the benefit of both _Expeditious Search_ and _Thorough Search_.
```
**Equipment** [desert clothing](https://2e.aonprd.com/Equipment.aspx?ID=2715), [cold weather clothing](https://2e.aonprd.com/Equipment.aspx?ID=2715), manual of cooking (Cooking Lore), manual of mapmaking (Cartography Lore), manual of the quahs (Shoanti Lore)
**Rumors** — Cinderlander, emberstorms, creatures
**Mounts** Desert horses have greater stamina
**Tools** Compass, a map with secret water holes labeled, a device that claims to detect incoming bullets from cinder cones and landsharks (detects ground tremors), fire shelter, ointment that claims to repel scorpions, snakes, and spirestalkers,  
**Spells & Magic Items** [create water](https://2e.aonprd.com/Spells.aspx?ID=1476), [environmental endurance](https://2e.aonprd.com/Spells.aspx?ID=1517), [shade hat](https://2e.aonprd.com/Equipment.aspx?ID=1322), [decanter of endless water](https://2e.aonprd.com/Equipment.aspx?ID=254), [explorer’s yurt](https://2e.aonprd.com/Equipment.aspx?ID=3022), [bivouac targe](https://2e.aonprd.com/Equipment.aspx?ID=3022), [restful tent](https://2e.aonprd.com/Equipment.aspx?ID=1071), 

**Unreliable** Most items with this trait are gimmicks—scams to take advantage of the uninitiated. When an item with this trait is used for the first time, make a DC 15 flat check. On a success it actually functions as described. Otherwise, it is useless.

```pf2e-stats
# Map of Water Sources
## Item 1

---
==unreliable==
**Price** 5 sp
**Usage** held in 1 hand; **Bulk** -

---
This is a map of the Cinderlands, showing secret sources of water. When you're on the map, a successful Survival check is not necessary to locate water rations.

```
```pf2e-stats
# Seismic Event Detector
## Item 3

---
==unreliable==
**Price** 2 gp
**Usage** held in 2 hands; **Bulk** L

---
Place this device on the ground in camp. It is capable of detecting approaching landsharks as well as ejections from cinder cones in the area. Grants a +2 circumstance bonus to initiative rolled in encounters with burrowing creatures and environmental hazards.

```
```pf2e-stats
# Fire Shelter
## Item 2

---
==unreliable== ==consumable==
**Price** 6 sp
**Usage** worn; **Bulk** L

---
This is a tarp made from special fire immune material. If you spend 1 minute securing it to the ground, one medium creature can crawl beneath it and remain safe from wildfires for up to 1 hour.

```
```pf2e-stats
# Pest Repellent
## Item 1

---
==unreliable== ==consumable==
**Price** 3 sp
**Usage** held in 1 hand; **Bulk** L

---
Applying this ointment for 1 minute, repels bugs both big and small. As *sanctuary* spell (save DC 25), but specific to insectile and reptile animals, and lasts for 12 hours.

```
```pf2e-stats
# No Worry Sippy Straw
## Item 5

---
==unreliable==
**Price** 5 gp
**Usage** held in 1 hand; **Bulk** L

---
The several elegant spirals in the length of this metal tube remove toxins and other unpleasant contaminants which may be present. The danger remains in the source, but consuming any liquid through this device prevents the user from being exposed to any poison or disease. Each time this device is used, attempt a DC 5 flat check, and on a success the sippy straw can be used again.

```
## Cinderlands Rumors

1. A ghost stalks the Cinderlands looking for revenge on his killer. (partly true, The Cinderlander is not a ghost)
2. The Shoanti are on the verge of war within the Quahs. (false, it’s with Korvosa)
3. A winter emberstorm is coming—an omen of cleansing. (who knows)
4. There is a herd of aurochs roaming the plateau so big it has a psychic presence. (false, though the herds are quite large)

Day 1: Tollday 13 Abadius