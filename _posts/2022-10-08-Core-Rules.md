---
title: Core Rules v0.0.6
date: 2022-10-7 12-15 +000
categories: [Bellum Caelum, rules]
tags: [rules]
pin: true
---

# Outline
BC is a 6mm scale alternating activations war game set in a mythical science-fantasy past where psychically ferocious space elves and hulking, cunning orcs battle against soulless mechanised undead abominations for the sake of all life in the galaxy. 

Measurements are made in centimetres, and all rolls are made with a regular 6 sided dice.

# Disclaimer
This is a work-in-progress alpha version of the game. Please consider all rules incomplete/unrefined. Feedback and suggestions, on both wording and the rules themselves, is encouraged. 

Thanks for taking a look!

# Units
Units can be one of four types; infantry, hero, vehicle, or titan. Each Type behaves in slightly different ways. All the information you need to know about your unit can be found on its data card. A single unit will always occupy one single base (for multi-base groups, see squadron below)

## Data Cards
A unit has the following stats, indicated on their data card:

- Movement (Mov) — a cm value. The maximum distance a unit can move in one action.
- Actions (Act) — the number of actions a unit can perform in one turn.
- Initiative (Ini) — the skill check difficulty for performing Reactions/overcoming Shock.
- Shooting (Sho) — the skill check difficulty ****for shooting attacks.
- Close Combat (Clo) — the skill check difficulty for close combat attacks.
- Aptitude (Apt) — the skill check difficulty for performing Powers.
- Defence (Def) — how well your unit can avoid or absorb attacks. The first number indicates how many dice to roll, the second is a modifier that can be applied to the rolls.
- Powers (Pow) — the number of powers that can be used in one action.
- Save— the skill check difficulty for shrugging damage.
- Wounds/Models — how much damage can be sustained before a unit is incapacitated, or in the case of infantry, how many models remain in the unit. Located at the bottom of the data sheet.

## Unit State
A unit may be in one of 4 states:

- Ready — the unit has not yet activated this round.
- Activated — the unit has performed it’s actions for this round.
- Reserved — the unit has not been deployed on the battlefield (see Rounds>Orders).
- Incapacitated — the unit has been reduced to 0 wounds. Remove the model(s) from the board.

Additionally, Ready and Activated units can also be Engaged. Engagement occurs when a unit is within 1cm of an enemy unit. While engaged, the total number of actions a unit may perform in one round are reduced by one. Infantry and Heroes cannot shoot or be shot at while engaged. 

Vehicles cannot be shot and can only shoot units with which they are engaged.

## Unit Type
### Infantry
Infantry units multiply the number of Attacks for their weapon by the number of models remaining in the unit (represented by an M in the stat), e.g. in a unit with Attacks M/0 and 6 models remaining, the unit will roll 6 attacks. 

The small vertical bar on the Models tracker indicates when a unit becomes Shocked (Rounds>Activations).

The Infantry class also includes mounted infantry and light vehicles. For the purposes of the rules these models behave exactly as regular foot-soldiers.

By their very nature, infantry usually carry lighter weapons. Unless otherwise stated, the number of attacks made by infantry against Vehicle units is halved, rounding up.

### Vehicles
Larger vehicles and large single-model infantry units are classified as vehicles.

Vehicles get bracketed as they lose wounds — their stats will reduce as indicated on their data card.

### Hero 
Hero models are single infantry models. They behave much like infantry models, but never suffer shock and for the purposes of the rules are always treated as being one model with multiple wounds.

Hero models cannot be targeted for ranged attacks if any friendly infantry unit is within 3cm of the Hero.

### Titan
Titans are the largest class of unit, representing the behemoth battle engines, god-like incarnations, and mammoth fighters of the BC universe. Each Titan has two data cards (or one double sided). One side has the same stat-line and rules as other data cards, the other is used for tracking wounds and bracketing on the various parts of the titan — effectively the titan acts as several units rolled into one.

Each part of the titan will have its own wounds characteristic and defence stat, and will bracket separate stats.

When an attack is made against a titan, the attacker must specify which portion of the titan they are targeting. All attacks are resolved against that portion only. Any excess damage is lost.

A titan may have two numbers separated by a slash as their Actions stat. This means the Titan can activate more than once in one turn. All orders must be issued during the Order phase as usual, and the activation must be taken in order of the numbers in the stat-line, e.g. 2/1 would mean first the two action activation must be made, then the one action activation.

# Weapons
A unit will have one or more weapons listed on its card. Weapons have the following stats:

- Range (Ra) — either a cm value or CC for close combat weapons.
- Attacks (At) — the number of attacks each instance of this weapon can make in one action, plus a power modifier that is added to each roll result.
- Damage (Da) — the number of points of damage each successful and unsaved hit causes.

A weapon will have a type that dictates how it behaves against unit types:

## Squadrons
Infantry units can be organised into larger groups, called squadrons. The limits for squadrons are marked on the unit’s data card as stars along the right side. Each star represents one unit. Only units sharing the same data card can be grouped into squadrons.

Squadrons allow several units to act as one large unit, receiving the benefits or penalties of e.g. aura abilities and powers cast on them.

Squadron sizes may also activate certain special rules (particularly for the Krogh).

Units in a squadron cannot become Shocked until only one unit remains in that squadron (see Activations>Shocked).

A squadron must remain in Formation at all times (see Actions>Move).

Orders are assigned to the whole squadron, not individual units.

Squadrons must be declared before the game begins, and cannot be disbanded in the middle of a game (except in the case of certain special rules).

# Rounds
A game of BC is separated into Rounds, each with three phases. The sequential activity of a round represents the tumult of battle, where in reality many of the actions would be occurring simultaneously. For this reason, all wounds and casualties are calculated at the end of a round.

## Orders
In the Orders phase, a number of action tokens equal to the unit’s Actions stat (after any modifiers) are placed facedown next to every unit, or alternatively on the unit’s data card. From round two, any units with a status of Reserved can be placed on the battlefield during the Orders phase. 

>**Deploying Reserves:** A unit in reserve can be deployed anywhere on the battlefield outside 15cm of an enemy unit. A unit that is deployed from reserve can only perform one Action this round, and that action cannot be Move. In addition, it cannot perform any reactions for this round. Reserve units can be deployed at any point during the Orders phase.
{: .prompt-info }

## Activations
Players roll off and the winner chooses whether to activate first or second. This roll is modified by their faction’s Speed characteristic (0 for the Krogh, 1 for the Nekhra, 2 for the Eldaer) . Players take it in turns to activate units starting with the elected player — turn over all tokens for the activated unit and resolve the orders. Orders can be resolved in any sequence.

A unit can perform the same action two or more times as part of a single activation, but suffers a cumulative skill check penalty of 1 to successive attempts. (In practice this means there is no penalty for moving twice)
> **Shocked**: An Infantry unit is Shocked when the number of remaining models falls below the marker on the Models indicator at the bottom of their datasheet, or when the infantry unit has taken more damage than models remaining in the unit/squadron. If a unit is Shocked, it cannot perform Orders as efficiently. After selecting the unit for Activation, but before performing any actions, perform one Initiative Skill Check for each order issued (usually 2). For each success the unit may perform one of its orders.
{: .prompt-info }

## Scoring & Resolving Damage
At the end of the round, casualties are resolved, scores noted, and the next round begins.

To score the round, follow the instructions that came with the mission.

To calculate wounds and casualties, for each unit that has taken damage this round, roll a number of dice equal to the total damage on that unit, trying to match or beat the unit’s Save characteristic. Reduce the damage by the total number of successful toughness checks. Any remaining damage is tallied as wounds. If a unit is reduced to 0 wounds or models, it is incapacitated and removed from play.

For squadrons, all wounds must be taken on one of the squadron’s units until all models in that unit are slain and the unit is incapacitated. However, if a unit is incapacitated in the course of resolving damage, any remaining damage is discarded, e.g. if after performing Save checks for a squadron of 2 infantry units, the total number of wounds is 5, but only 3 models remain in one of the units, that unit is incapacitated, and the remaining two points of damage are discarded, leaving the rest of the squadron unscathed.

# Actions
For each of their Action stat points, a unit can perform one of five actions (and/or any mission specific actions).

Actions are decided at the beginning of a round in the orders phase. When a unit is activated to perform its actions, if one or more of the actions is no longer possible (e.g. a unit has been ordered to fight but the enemy has moved out of engagement), that action is discarded.

All the actions in an activation must be performed in sequence without interruption, and they can be performed in any order.

## Move
Infantry can move in any direction and turn an unlimited number of times. Total distance travelled in one action must not exceed the unit’s movement in cm. If the model passes over or within 1cm of an enemy unit during its movement, the action is immediately terminated and both units become Engaged. Likewise, if the unit finishes its movement within 1cm of an enemy, both units are Engaged. For details on resolving actions when Engaged, see below.

> Squadrons must remain in Formation for the duration of the battle. This means that any single unit in the squadron can be no more than 1cm from any other single unit in the squadron. Each units movement is calculated individually — measure and move each unit by itself. 
If a unit is removed from play or otherwise moved, breaking Formation, all remaining units in the squadron must regroup as their first action during their next activation. Regroup by moving any or all units up to that unit’s Movement until all units are in formation again. If for some reason it is impossible to regroup during the squadron’s next activation, the player must remove units from their squadron until formation has been achieved. These removed models count as incapacitated.
{: .prompt-info }

>If a unit enters into engagement as part of its own move, it may only perform any remaining orders if those orders are Fight. Any other remaining orders must be discarded.
If a unit that is engaged is ordered to move (and thus leave engagement), roll an initiative dice. If the roll fails, the unit does not move. If the roll succeeds, the unit may make any normal move action.
{: .prompt-info }

## Shoot
A unit may fire any or all of its weapons in one action. It can split fire across multiple targets, but all shots from one instance of a weapon must be made against a single target. E.g. a unit of 10 models with Attack M/0 guns may split fire, with 9 models shooting at one target, and one model shooting at another (i.e. 9 shots one way, 1 the other), but a single Hero with one Attack 4/+1 gun could not split those 4 attacks — all would have to target a single unit.

The selected target must be within LoS (see below) of the target. 

The attacker rolls a number of dice equal to the first number in the attacks characteristic of the weapon being used, trying to match or beat their Shooting Skill (plus or minus any applicable modifiers).

Simultaneously the defender rolls a number of dice equal to the first number in their Defence stat.

Always resolve attacks for each weapon one at a time, but always resolve all the attacks for one type of weapon against a single target at the same time. (i.e. if a unit has 6 cannon shots and 4 blaster shots, and is shooting all shots against one target, resolve all cannon shots, allowing for all Defence saves, then resolve all blaster shots, again allowing for all Defence saves).

When failed shots have been removed from the attackers pool, add the second number from the Attacks stat to the attackers roll, and the second number from the Defence stat to the defenders rolls. Any Defence roll that exceeds an Attack roll cancels out that Attack.

Each successful hit that is not cancelled by a successful save causes damage indicated by the weapon’s Damage statistic, which should be tallied and resolved into wounds at the end of the battle round (see Rounds>Scoring & Resolving Damage). 
However, one single attack cannot do more damage than the wounds characteristic of a single model in the targeted unit. For example, 5 successful hits of a Dam 2 weapon firing on a unit of 10, single wound infantry models will do 5 damage, not 10. The same shots firing at a 10 wound vehicle, however, will do 10 damage, as the wounds characteristic of the vehicle is greater than the damage characteristic of the weapon.
> If an unobstructed line can be drawn from anywhere on the shooting unit to anywhere on the targeted unit, the target is said to be within LoS. Obstructions can include terrain, and also friendly and enemy units. BC is designed to be a fun game, so use common sense when drawing LoS — LoS from the corner of a base to the tip of an aerial is a feel-bad for the targeted player, and likewise challenging every LoS call of an opponent is petty.
{: .prompt-info }

## Fight
When a unit is in engagement with another unit, it may perform a fight action against that unit.

The attacking unit can attack with all it’s Range: CC weapons (one at a time), checking against its Close Combat stat. Roll a number of dice equal to the first number of the weapon’s Attack characteristic.

The defending unit can elect to roll on its Defence stat, or one of its Range: CC weapons. The outcome for these two defensive options is slightly different. 

Always resolve attacks for each weapon one at a time, but always resolve all attacks for one type of weapon against a single target at the same time.  (i.e. if a unit has 6 knife attacks and 4 fist attacks, and is targeting all attacks against one target, resolve all knife attacks, allowing for all parry saves, then resolve all fist attacks, again allowing for all parry saves).

Remove failed rolls from the attackers pool.

If the defender has chosen to use a weapon to defend, remove failed rolls (i.e. rolls below the defenders Close Combat stat) from the their pool.

Add the second number from the stat (Attack or Defence) to each result.

Each Defender result that exceeds an attacker result cancels that attack. 

Each successful attacker hit causes damage indicated by the weapon’s Damage statistic, which should be tallied and resolved into wounds at the end of the battle round (see Rounds>Scoring). 

If the Defender chose to defend with a weapon, and after resolving all attacks there are still Defence rolls remaining, the attacker damage instead.

Unlike shooting, wounds from close combat attacks always carry. This means even when attacking single wound infantry models, one successful attack with a Damage characteristic of 5 will do 5 points of damage, not one, as it would in shooting.

For rules on leaving engagement, see Move above.

## Cast
Many units have access to Aetheric or Vaagh powers, or esoteric technology. These will be listed on the unit’s datasheet, along with the powers rules and any modifiers to the casting skill check (e.g. a power may be listed as Apt +2, meaning a unit with a Apt 2+ must roll 4 or over to cast the power). A unit may cast a number of powers equal to their Powers stat. A unit may not cast the same power twice in one activation. Roll against the unit’s Aptitude skill, determining successes in accordance with the power’s rule.

## Pass
The unit performs no action. The pass token is also used to represent mission actions, or can be used to obfuscate a disengagement order.

# Special Rules
Special Rules are applied to units through powers and commands, or found on their datasheet. The rules are universal, so every unit that has or gains a special rule uses the same version of that rule, without exception. 

Special Rules supersede core rules and datasheet stats. 

Special Rules are split into two categories; Advantages and Disadvantages. Advantages always improve the performance of the affected unit, disadvantages always hinder them.

The Special Rules Enhance and Vitiate are large, catchall rules that describe the improvement or impediment of data sheet stats. They will always be qualified by a stat name and a number (𝑥 below), and often also a limit. These qualifications indicate the stat that is affected and by how much, e.g. **Enhance Toughness 2 min. 2+** would improve a Toughness characteristic by 2, to a minimum of 2+.

For stats used in Skill Checks, the number is applied to the roll, for absolute stats, like Movement or Powers, the number is applied to the characteristic itself.

If a Special Rule is qualified with a ‘within 𝑦 cm’ statement, this means all units within 𝑦 cm radius of the affected unit are also affected by the rule, e.g. **Vitiate Shooting 2 within 12cm** would impair the shooting characteristic of all models within 12cm of the affected model by 2.

## Reactions
Players can perform a number of Reactions per round equal to the faction’s speed characteristic +1 (i.e. Aeldar 3, Nekhra 2, Krork 1).

Only Ready units may be selected to perform a Reaction. 

Reactions are performed during an opponents Activation.

The player declares the Reaction after their opponent turns over their order tokens, but before any of those actions have been resolved (e.g. the Reaction must be declared before an opponent declares the targets of their attack, etc). The reaction can be any Action, but before resolving the action, the player must roll an Initiative skill check. If the check fails, the Reaction fails. If the Initiative check succeeds, the Reacting unit may perform the selected Action. 

Whether the Reaction succeeds or not, the reacting units status changed to Activated, and any orders that unit had are discarded.

When the the reacting units initiative check and actions have been resolved, the opponent may continue with their turn 

A player can react multiple times before allowing their opponent to continue, but all reactions must be declared at the same time. For example, it is not legal to attempt a reaction, and upon it’s failure decide to react with a different unit.

A single unit can only react once per opponent Activation.