**Actions** Characters begin each day with 6 hexploration actions. Each one represents roughly 4 hours of activity. Typically while traveling, 4 of these are taken up with resting and group actions, leaving 1 or 2 for individual characters to undertake their own activities. Other times, the focus is on exploring and surveying. In this mode, there is less travel and searching for campsites, and more room for individual activity.

**Group** These are activities undertaken by all members of your group. Each member must spend the required number of actions to use one and its outcomes apply to each member of the group. Splitting into multiple groups may allow characters with higher movement speeds to arrive at a destination with more actions to spare.

**Safe Activities** with this trait are usually reserved for downtime and cannot be done during exploration. However, if the group is camping in a secure location such as a fortified campsite, activities with the safe trait can be used.

**Random Encounters** Make a flat check against the **Encounter DC** for each move action used by each group. Another check is made while camping against a number 2 higher than the **Encounter DC**.
```pf2e-stats
# Travel `[one-action]`

---

==exploration== ==group== ==move==

You move a distance on the hex map based on your **Travel Speed**, which is equal to the speed of the slowest member in your group. Choose an adjacent hex and consult the table below to determine how much of your Travel Speed is required to enter that hex.

**Forced Marches** The second time you undertake this activity in a single day, you take a -5 status penalty to your Travel Speed. The third and all subsequent times, this penalty is -10. After a forced march, each character must attempt a Fortitude save against the **Zone DC**.
	**Failure** You become fatigued.
	**Critical Failure** You become fatigued and increase your drained level by 1.

| Entering Hex | Movement Cost |
| --- | --- |
| Open Terrain (plains, most roads) | 5 |
| Rugged Terrain (typical forests, desert, hills) | 10 |
| Extreme Terrain (steep mountains, swamp) | 15 |
| Flying or Sailing (fair weather) | 5 |
| Flying or Sailing (foul weather) | 10 |
| Boat Downriver | 5 |
| Boat Upriver | 10 |


```

```pf2e-stats
# Explore an Area `[one-action]`

---

==concentrate== ==exploration== ==group== ==move==

**Requirements** A suitable base camp.

---

Establishing a central point that you use as a reference, you search the nearby wilderness. You never stray too far, but instead try to find vantage points to gain a better perspective. 

**Find Special Features** You automatically find any special feature that doesn’t require a check to find, and you attempt the appropriate checks to find hidden special features, located in your current hex or any of the adjacent hexes.

**Relocation** You can choose to relocate your group to an adjacent hex upon completion of this activity.
```
```pf2e-stats
# Create Survey `[one-action]` to `[three-actions]`

---

==concentrate== ==exploration==

**Requirements** Writing Set, Explored Area

---

Once you have explored an area and discovered all key landmarks, you can create an accurate survey. Make a Crafting (planning/development survey), Nature (geological or weather survey), Society (political survey), or Survival (geographic survey) check (typically at a trained or expert DC).
	**Critical Success** Progress survey 5 steps
	**Success** Progress survey 3 steps
	**Failure** Progress survey 1 step 
	**Critical Failure** No progress
	**`[two-actions]`** Turn a critical failure into a normal failure.
	**`[three-actions]`** Your result is one degree of success better than it would be by numbers alone.

```
```pf2e-stats
# Prepare Campsite `[one-action]` or `[free-action]`

---

==exploration== ==move==

You search the current hex for a safe and secure location to make camp and then set up the campsite itself by attempting a Survival check against the Zone DC. Once a campsite is prepared, you can use the Prepare Campsite activity in this same hex again in the future (but no more than once per 24 hours) to automatically achieve the same degree of success as a free-action.
	**Critical Success** You find the perfect spot for a camp. Flat checks to determine encounters at the campsite for the next 24 hours have a DC 2 higher than normal, and the first success is ignored.
	**Success** You find a serviceable spot for a camp and for Camping activities.
	**Failure** Your campsite will work, but it's not the best. Campsite activities that require checks take a –2 penalty.
	**Critical Failure** The campsite is a mess. You can use it to rest and to perform daily preparations, but it isn't good enough to allow for Campsite activities at all.
```
```pf2e-stats
# Fortify Camp `[one-action]`

---

==exploration== ==move==
**Requirements** trained in crafting, a prepared campsite

Using nearby resources and features, you turn the camp into a secure location; helping to protect against attacks and weather, while also making it more comfortable. 

**Safe** During both the construction and for as long as it stays up, this camp is secure enough take undertake ==safe== activities. Once finished and for as long as it lasts, flat checks to determine encounters at the campsite have a DC 2 higher than normal, and the first success is ignored.

**Duration** With no skill check necessary, the campsite will remain fortified for one camping session, after which it remains a prepared campsite. You can attempt a Crafting check against the Zone DC to make more lasting fortifications.
	**Critical Success** As success, but if you spend three actions fortifying this camp, it becomes a permanent feature.
	**Success** Your fortifications last for 1 additional day; you may spend additional actions (up to `[three-actions]`) and for each additional action you spend it lasts for three more days.
	**Failure** Your fortifications will not hold any longer than this camping session.
	**Critical Failure** Your attempts have gone so badly all camping activities are disrupted! You must find another campsite.
```
```pf2e-stats
# Craft `[two-actions]`

---

==camping== ==concentrate== ==safe==
**Requirements** All the requirements of the normal downtime activity Craft.

This works like the normal downtime activity Craft, including spending several days to craft the item. Each Craft activity counts for 1 day. The days need not be consecutive, but the items is useless until all days have been finished.

**Note** If the item requires only four hours to craft, this activity loses the ==safe== trait and takes only `[one-action]`.
```
```pf2e-stats
# Long Term Rest `[two-actions]`

---

==camping== ==healing== ==safe==
**Requirements** Same as the normal downtime activity.

This works like the normal downtime activity. Long Term Rest `[two-actions]` and with Rest `[two-actions]` are both required in a 24 hour period. If you undertake any activity in addition to those more strenuous than Relax `[one-action]`, you gain no benefit from your long term rest in that day. Depending on your situation, the GM may decide that your foolish exertions cause a setback in your recovery process.
```
```pf2e-stats
# Treat Disease `[two-actions]`

---

==camping== ==concentrate== ==healing== ==safe==
**Requirements** All the requirements of the normal downtime activity Treat Disease.

This works like the normal downtime activity Treat Disease. However, on a critical failure, some aspect of the disease (noise from the patient, smell of festering, etc) may attract unwanted attention! Immediately check for a random encounter.
```
```pf2e-stats
# Cook Basic Meal `[one-action]`

---

==camping== ==manipulate==

Expend 2 basic ingredients per serving you wish to prepare, as well as 1 day's rations, or provisions from Subsisting, per serving. Once the group finishes all camping activities and the characters have chosen which meals they wish to eat, attempt a DC 22 Survival, DC 20 Crafting, or DC 18 Cooking Lore check to determine the effectiveness of your basic meal.
	**Critical Success** It's delicious! A character who eats this meal recovers Hit Points equal to their CON (minimum 1) multipled by **twice their level** when they rest and choose that benefit during this camping sessions instead of the normal amount. They also gain a +1 status bonus to all saving throws until they complete their daily preparations, or begin adventuring again.
	**Success** It's pretty good! A character who eats it gains a +1 status bonus to all saving throws until they complete their daily preparations, or begin adventuring again.
	**Failure** It fills bellies, but has no other effects.
	**Critical Failure** It wreaks havoc. A character who partook of this meal becomes sickened 1 until after they rest and complete their daily preparations.

```
```pf2e-stats
# Cook Special Meal `[one-action]`

---

==camping== ==manipulate==
**Requirements** knowledge of the recipe

Choose a special meal whose recipe the group knows and then expend the basic and special ingredients required for each serving you wish to prepare, as well as 1 day's rations, or provisions from Subsisting, per serving. Once the group finishes all camping activities and the characters have chosen which meals they wish to eat, attempt a Survival, Crafting, or Cooking Lore check to determine the effective of your special meal. The DC of the check varies by recipe. Unless the special meal's description says otherwise, its effects last until the next time the party prepares a camp or 24 hours, whichever comes first.
	**Critical Success** Varies by recipe.
	**Success** Varies by recipe.
	**Failure** No special benefit but it's the thought that counts.
	**Critical Failure** Varies by recipe.


**Recipes** Special meal recipes are formulas you can purchase at a settlement or discover on your own with the **Discover Special Meal** activity.

**Repeatable** You can be attempt this activity multiple times during a camping session, but each attempt must use a different recipe.

**Sick Campers** A character who is sickened can't eat a special meal or gain its benefits.

```
```pf2e-stats
# Discover Special Meal `[one-action]`

---

==camping== ==manipulate==

**Requirements** trained in Cooking Lore

Choose a common recipe from the list; the recipe must be of a level equal to or less than the level of the zone you're camping in. Expend twice the normal amount of ingredients required to prepare 1 serving of the special meal, then attempt that special meal's Cooking Lore check.
	**Critical Success** You discover the special meal and add it to the list of recipes the party knows. In addition, your research was efficient, and you recover half of the ingredients you had to expend to attempt this activity.
	**Success** As critical success, but you do not recover any ingredients.
	**Failure** You fail to discover the special meal and do not recover any ingredients.
	**Critical Failure** As failure, but also you expose yourself to the special meal's critical failure effect while performing an unwise taste test.

| Special Meal | Rariity | Level |
| --- | --- | --- |
| Hearty Meal | Common | 0 |
| Jeweled Rice | Common | 0 |
| Fish on a Stick | Common | 1 |
| Haggis | Common | 1 |
```

```pf2e-stats
# Hunt and Gather `[one-action]`

---

==camping== ==move==
**Requirements** trained in Survival

This supplements the food from Subsisting with additional ingredients you can use to cook basic or special meals, gaining greater effects than simply eating rations alone. Attempt a Survival check against the Zone DC or a Hunting Lore check against the 2 less than the Zone DC.
	**Critical Success** You find a number of basic ingredients equal to twice the zone's DC, plus 4 special ingredients. If you're Hunting and Gathering in a zone that's at least level 7, increase the number of special ingredients found to 8; if you're doing so in a zone that's at least level 14, increase it to 22.
	**Success** You find a number of basic ingredients equal to the Zone DC, plus 1d4 special ingredients. If you're Hunting and Gathering in a zone that's at least level 7, increase the number of special ingredients found to 2d4; if you're doing so in a zone that's at least level 14, increase it to 3d4.
	**Failure** You find a number of basic ingredients equal to the Zone DC.
	**Critical Failure** You find 1d4 basic ingredients. In addition, you've attracted attention. Make an additional random encounter check.
```
```pf2e-stats
# Learn from a Companion `[one-action]`

---

==camping== ==concentrate==
**Requirements** The companion to be learned from must be camping with you, and they must be at least friendly.

Companions offer specialized campaing activities. Normally, in order for you to be able to attempt one of these specialized activities, that companion must be present in the camp as well, but this activity allows the companion to attempt to teach the party how to perform the activity on their own. Attempt a DC 20 Perception check.
	**Critical Success** You learn the companion's special activity. Any character who meets that activity's requirements (see table) can now perform that activity even when the companion isn't in the camp.
	**Success** You make progress in learning the special activity but require at least one more day to master it. If you attempt to Learn from this Companion the next time you camp, the result of that check is improved by one degree of success from the result rolled.
	**Failure** You fail to learn anything from the companion.
	**Critical Failure** You fail to learn from the companion, who grows frustrated with the party. No further attempts to Learn from this Companion can be attempted during this camping session.


| Activity | Companion | Requirements |
| --- | --- | --- |
| Blend into the Night | Harrim | Trained Religion, worships Groetus |
| Bolster Confidence | Linzi | Expert in Performance |
| Enhance Weapons | Amirir | Expert in Crafting |
| Maintain Armor | Valerie | Exert in Crafting |
| Undead Guardians | Jaethal | Expert in Religion |

```
```pf2e-stats
# Organize Watch `[one-action]`

---

==camping==
**Requirements** expert in Perception

You take the lead on organizing the camp's watch rotation, optimizing shifts, and scouting the surrounding area to determine which approaches to the camp are most liekly to be used by enemies. Attempt a Perception check against the Zone DC.
	**Critical Success** As success, plus the camp's watch is efficient. One character in the rotation can stand watch as a `[free-action]`.
	**Success** All characters gain a +2 status bonus to Perception checks and DCs during their shift on watch.
	**Failure** No additional benefits.
	**Critical Failure** As failure, but you may have attracted unwanted attention. Make an immediate random encounter check.
```
```pf2e-stats
# Stand Watch `[one-action]`

---

==camping== ==concentrate==

You remain awake, checking approaches, counting heads, and maintaining the camp's defenses while the rest of your party is sleeping or otherwise unwary. Since you are not unconscious, you do not suffer from the -4 status penalty to Perception and not implicitly blinded. On the contrary, you benefit from the +2 status bonus to Perception checks and DCs from any plans or protocols put in place from an organized watch.
```
```pf2e-stats
# Provide Aid `[one-action]`

---

==camping== ==concentrate==
**Requirements** The ally is willing to accept your aid on a camping activity that requires a check for success.

You aid another character in their camping activity. When you Provide Aid, attempt a skill check of a type decided by the GM. The typical DC is 15, but the GM might adjust this DC for particularly hard or easy tasks. You can Provide Aid as many times as you want during a camping session, but remember that circumstance bonuses granted by Provide Aid do not stack.
	**Critical Success** You grant your ally a +2 circumstance bonus to the activity. If you're a master with the check you attempted, the bonus is +3, and if you're legendary, it's +4.
	**Success** You grant your ally a +1 circumstance bonus to the activity's check.
	**Critical Failure** Your ally takes a -1 circumstance penalty to their activity's check.
```
```pf2e-stats
# Relax `[one-action]`

---

==camping==

You spend time listening to campfire stories, chatting, reading, meditating, napping, or otherwise simply relaxing. Choose one:
	**Relaxed** You gain a +1 circumstance bonus to the next check you make in order to resolve a camping activity, provided that check happens during this camping session.
	**Recovered** If you're suffering a status penalty from a bad campfire story, remove that penalty now.
	**Rest Well** Choose 1 more benefit from resting at the end of this camping session.
```
```pf2e-stats
# Tell a Campfire Story `[one-action]`

---

==auditory== ==camping== ==concentrate== ==emotion== ==mental==

You tell a rousing story, perhaps one of your previous adventures or something that was in turn told to you around a campfire. The GM might award a +1 circumstance bonus to your check if the story is relevant to your recent or upcoming adventures, or if it reflects one or more characters' personal stories. Attempt a Performance check against a DC equal to that set by your own level.
	**Critical Success** You inspire your allies dramatically. For the remainder of the camping session, your allies gain a +2 status bonus to attack rolls, saving throws, and skill checks made during encounters at the campsite. The bonuses end as soon as daily preparations being after resting is concluded. If an ally spent the time relaxing, they can also choose to reroll a failed roll at any time once during the remainder of the camping session while the status bonus persists; this is a fortune effect.
	**Success** You inspire your allies. As critical success, but the bonus is +1. An ally who spent that time relaxing receives a +2 status bonus but does not receive the reroll effect granted by a critical success.
	**Failure** Your allies are unmoved and receive no benefits.
	**Critical Failure** Your story distracts or unsettles your allies. They each take a -1 status penalty to skill checks until they relax or until they begin daily preparations.
```
```pf2e-stats
# Bolster Confidence `[one-action]`

---

==auditory== ==camping== ==concentrte== ==mental==
**Requirements** Linzi is camping with you.

Linzi's enthusiasm inspires everyone around her. Checks on all other camping activities while Linzi does so gain a +1 circumstance bonus. If Linzi is master in Performance this becomes a +2 circumstance bonus.
```
```pf2e-stats
# Enhance Weapons `[one-action]`

---

==camping== ==concentrat== ==manipulate==
**Requirements** Amiri is camping with you.

Amiri spends her time in camp sharpening the group's weapons, bolstering grips and handles, or festooning blunt weapons with temporary stone weights designed to maximize damage. Each PC chooses one melee weapon. That melee weapon gains a +1 circumstance bonus to damage rolls during the next encounter it's used in; this bonus expires at the end of that encounter or after 24 hours, whichever comes first.
```
```pf2e-stats
# Rest `[two-actions]`

---

==healing==

Though resting typically happens at night, you gain the same benefits for resting during the day. Either way, once rest is taken, you are immune to its benefits for 24 hours. When you complete this activity choose one from the list of benefits. If you complete this activity after having eaten, with shelter and comfort, such as in a prepared campsite, choose 2.
	**Regain Hit Points** equal to your CON (minimum 1) multiplied by your level. You can choose this benefit more than once.
	**Lose the fatigued condition**
	**Reduce the severity of doomed and drained by 1**
	**Regain spells**
```