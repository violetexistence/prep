# Sredna

**Rules** In sredna, two contestants face one another on their hands and knees with their foreheads spaced just over a foot apart. A leather loop is placed around the competitor’s heads, like a headband, so that the contestants are bound to one another. When the game begins, each contestant stares his opponent in the eye while slowly attempting to crawl backwards. The resulting tug-of-war results in extreme pain as the leather digs into the soft part of the back of the neck and skull. At some point, one of the competitors relents, acknowledging defeat by bowing his head, causing the strap to roll over the top. Games of sredna typically last for mere seconds, but two evenly matched opponents might duel much longer. In such cases, standoﬀs occur frequently.

When a sredna match begins, each contestant must spend three “breaths” (3 rounds) staring into the other’s eyes before attempting to pull. Pulling before the 4th round is an immediate disqualification. Intimidation and patience are almost as important tools to win sredna matches as is strength. Actions are chosen in secret and revealed simultaneously at the beginning of each round.

During these initial 3 rounds, the contestants can use Growl or Focus
On the 4th and subsequent rounds, the contestants can use Pull, Brace, or Yank.

Spectators can act each round as well, choosing from Cheer, Jeer, or Analyze. Their actions need not be chosen in secret. Influence other than these, such as magical influence, is likely to get their contestant disqualified.

**Stamina Pool** Each contestant begins with a number of stamina equal to their CON. When your stamina pool is empty, your head bows and the leather loop falls off your head.

[[Eats What He Kills]]
**Stamina Pool** 7 **Fortitude** DC 35, **Reflex** +22, **Will** +20, **Athletics** DC 37, **Intimidation** DC 31
If he is reduced to 3 or fewer stamina, Eats What He Kills enters barbarian rage, increasing his ferocity but limiting his tactics. If the contest ends while he is still raging, his burn riders will restrain him until it ends.
```pf2e-stats
# Rage

---
==barbarian== ==concentrate== ==emotion== ==mental==

Enter a frothing rage, gaining 1 stamina and increasing both Athletics and Fortitude DCs by 2. You cannot use actions requiring concentration until the rage subsides. Rage lasts for 1 minute or until you fall unconscious, whichever comes first. You can't voluntarily stop raging. Once you stop raging, you can't gain the stamina from this action again for 1 minute.
```

#### Contestant Rounds 1-3
```pf2e-stats
# Focus

---
==concentrate==

Steel yourself for the impending pain and struggle. Attempt a Will save against your opponent's Intimidation DC.

**Critical Success** Gain 2 Stamina
**Success** Gain 1 Stamina
**Critical Failure** Lose 1 Stamina
```
```pf2e-stats
# Growl

---
==emotion== ==fear== ==mental==

Attempt an Intimidation check against your opponent's Will DC to shake their resolve.
**Critical Success** Your opponent loses 2 stamina
**Success** Your opponent loses 1 stamina
**Critical Failure** Your opponent gains 1 stamina
```
#### Contestant Round 4+
```pf2e-stats
# Pull

---
==attack==

Attempt an Athletics check against your opponent's Fortitude DC forcing them to bow their head.

**Critical Success** Reduce your opponent's stamina by 2
**Success** Reduce your oppponent's stamina by 1
**Failure** Reduce your own stamina by 1
**Critical Failure** Reduce your own stamina by 2

---
**Counter** This action gains a +2 circumstance bonus against yank.

**Countered By** This action suffers a -2 circumstance penalty against brace.
```
```pf2e-stats
# Brace

---
==attack==

By locking your body in position, you hope to force your opponent to expend tremendous energy to move you. Attempt a Fortitude save against your opponent's Athletics DC.

**Critical Success** Your opponent's stamina is reduced by 2
**Success** Your opponent's stamina is reduced by 1
**Failure** Reduce your own stamina by 1
**Critical Failure** Reduce your own stamina by 2

---
**Counter** This action gains a +2 circumstance bonus against pull.

**Countered By** This action suffers a -2 circumstance penalty against yank.
```
```pf2e-stats
# Yank

---
==attack== ==concentrate== ==mental==

Waiting for the right moment, you pull viciously to the side, hoping to catch your opponent overcommitted. Make a Perception check against your opponent's Reflex DC.

**Critical Success** Reduce your opponent's stamina by 2
**Success** Reduce your opponent's stamina by 1
**Failure** Reduce your own stamina by 1
**Critical Failure** Reduce your own stamina by 2

---
**Counter** This action gains a +2 circumstance bonus against brace.

**Countered By** This action suffers a -2 circumstance penalty against pull.
```
#### Spectator Actions
```pf2e-stats
# Cheer

---
==emotion== ==mental==

Attempt a Diplomacy check against your target's Will DC to inspire their next Brace, Pull, or Yank.

**Critical Success** Apply a +2 status bonus, or +3 if you're a master in Diplomacy
**Success** Apply a +1 status bonus
**Critical Failure** Apply a -1 status penalty
```
```pf2e-stats
# Jeer

---
==emotion== ==mental==

Attempt a Deception or Intimidation check against the opponent's Will DC to affect the DC of the next Brace, Pull, or Yank.

**Critical Success** Reduce the DC by 2
**Success** Reduce the DC by 1
**Critical Failure** Increasse the DC by 1
```
```pf2e-stats
# Analyze

---
==concentrate== ==secret==

Studying the contestants, you can anticipate one of their moves. Attempt a Perception check against your target's Athletics DC.

**Critical Success** You know the target's next two actions.
**Success** You know the target's next action.
**Failure** You get no information.
**Critical Falure** You incorrectly predict the target's next action.
```