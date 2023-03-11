---
title: Damage
layout: default
permalink: /damage
nav_order: 3
parent: Character
---
{% include toc.html %}

# Damage

Hit protection represents near misses, stunning blows, stamina depletion, superficial wounds and bruises, and so on. 

When damage reduces character's hit protection to zero or below, the character must roll on the death and dismemberment table. When hit again at zero or negative hit protection, the character must roll again on the death and dismemberment table. 

NPCs that are lowered to zero hit protection die.

Some damage may bypass hit protection and outright kill a character or immediately force a roll on the death and dismemberment table.

## Death and Dismemberment

As soon as a character is dropped to zero hit protection, they must roll on the permanent injury table (rolling 3d6 plus current hit protection, typically 0 or a negative number). The table below describes the type of injury in vague terms along with mechanical impacts. Describe injuries to the comfort level of your table.

Injuries should inflict penalties that make sense in the fiction. For example, a treatable leg injury should impede movement. Trying to use the injured body part should impose disadvantage on a roll.

| 3d6 + HP    | Deadliness                               | Ripping                                | Blunt                                                     | Shocking                                                                | Caustic                                     | Toxic                                                                                  |
| ----------- | ---------------------------------------- | -------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------- | -------------------------------------------------------------------------------------- |
| -1 or below | Grisly and instant death                 |                                        |                                                           |                                                                         |                                             |                                                                                        |
| 0           | Instant death                            |                                        |                                                           |                                                                         |                                             |                                                                                        |
| 1-2         | Doomed: Death in 1 round                 | Fatal wound, disadvantage on all rolls | Fatal trauma, disadvantage on all rolls                   | Organ failure, disadvantage on all rolls                                | Fatal burns, disadvantage on all rolls      | Organ failure, disadvantage on all rolls                                               |
| 3-4         | Doomed: Death in 1d4 rounds              | Fatal wound, disadvantage on all rolls | Fatal trauma, disadvantage on all rolls                   | Organ failure, disadvantage on all rolls                                | Fatal burns, disadvantage on all rolls      | Organ failure, disadvantage on all rolls                                               |
| 5-6         | Dying in 1d4 rounds without intervention | Head wound, unconscious for d4 rounds  | Head trauma, disadvantage on all rolls                    | Internal bleeding                                                       | All senses and speech are destroyed         | Vomiting, oozing, or bleeding; disadvantage until a long rest                          |
| 7-8         | Dying in 1d4 rounds without intervention | Severed or nearly severed arm          | Unconscious for d4 rounds, disadvantage until a long rest | Brain trauma, unconscious for d4 rounds, disadvantage until a long rest | Destroyed arm                               | Bleeding from eyes, nose, pores; permanently make saves against toxins at disadvantage |
| 9-10        | Dying in 1d4 rounds without intervention | Severed or nearly severed leg          | Unconscious for d4 rounds                                 | Brain trauma, disadvantage until a long rest                            | Destroyed leg                               | Bleeding from pores; disadvantage until a long rest                                    |
| 11-12       | Dying in 1d4 rounds without intervention | Arterial or gut wound                  | Internal bleeding                                         | Suffocation, disadvantage until a long rest                             | Lung damage, disadvantage until a long rest | Bleeding from eyes and nose; disadvantage until a long rest                            |
| 13-14       |                                          | Mangled arm, treatable                 | Broken arm, treatable                                     | Unconscious for d4 rounds, disadvantage until a long rest               | Burned arm, treatable                       | Toxic blood; permanently heal at a rate of 1 HP per rest                               |
| 15-16       |                                          | Mangled leg, treatable                 | Broken leg, treatable                                     | Unconscious for d4 rounds                                               | Burned leg, treatable                       | Compromised immunity; permanently make saves against toxins at disadvantage            |
| 17-18       |                                          | Slashed eye, treatable                 | Dazed; lose next action                                   | Dazed; lose next action                                                 | Burned eye, treatable                       | Nausea, inability to concentrate; disadvantage on all rolls                            |


## Environmental Damage

- Non-magical fire (Caustic), 1d6
- On fire (Caustic), 2d6 damage per round
- Lava (Caustic), instant death
- Acid (Caustic), 1d6 damage 
- Drowning (Shocking)
	- After 3 + str rounds of holding breath, roll on death and dismemberment table every subsequent round
- Freezing water (Shocking), 1 HP per round until warmed
- Non-magical lightning (Shocking), 3d6 damage **and** roll on death and dismemberment table
- Falling (Blunt), 1d6 damage per 10 feet, to a maximum 10d6
- Rocks falling (Blunt), 3d6 damage
- Poison (Toxic), damage amount depends on the poison

## Ambush damage

If a character is ambushed, the damage dice are doubled.

## Conditions

Some attacks inflict a condition. The following list is non-exhaustive and some monsters and environments may have special effects inflicting unique conditions.

- Exhausted: Disadvantage on all rolls
- Paralyzed: Unable to make any movement
- Grappled: Speed is 0, disadvantage on all rolls except to break the grapple
- Charmed: Acting friendly towards the charming creature
- Blind: Unable to see
- Deafened: Unable to hear
- Stunned: Unable to make significant movements
- Injured: All actions are done at disadvantage and at half speed 

## Stabilizing 

An ally may try to stabilize a character who is at or under zero hit protection by rolling an ability check, casting a spell, using herbs, or some other manner of healing. 

### Death 

When a character dies, write down their fate on the back of the character sheet. The character sheet may be ritualistically burned, buried, or sent off in a funeral boat *later* because the player should roll up another character (or ideally have another character waiting in the wings) to get back into the game.

### Convalescing

Make note of any linger injury from the [Death and Dismemberment](#Death%20and%20Dismemberment) table. All characters who have gone below zero hit protection and been stabilized must rest. 

Characters are restored after a number of [downtime cycles](downtimecycle#Convalescing) equal to the lowest result of Ld6. For example, a level 4 character rolls 4d6, resulting in a 3, 3, 5, and 6. The lowest number is 3, so the character's ability is restored after 3 downtime cycles.

## Resting

A short rest takes 1 hour. 

A long rest takes 8 hours, 6 of which must be spent asleep. 

| Conditions                                 | Restored HP |
| ------------------------------------------ | ----------- |
| Long rest in town or wilderness, with meal | 100%        |
| Wilderness, safe short rest                | L x d8      |
| Short rest (with meal) in dungeon          | 1d8         |

Long rests in a dungeon are inadvisable and are likely to fail. 

Resting must be safe and include food, drink, and (for long rests) sleep. Any interruption removes all benefits. The additional effects of ineffective resting follow: 

- **Hunger**. If characters do not eat in a day, they may not heal after their rests.
- **Sleep deprivation**. After a night of not sleeping, characters must roll at disadvantage until they rest. They do not heal from the rest. 
- **Thirst**. After one day of not drinking, characters must roll at disadvantage until they drink.  They do not heal from the rest. After three days, they must make DC 15 strength saves every hour or die. 