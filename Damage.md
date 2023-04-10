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

NPCs that are lowered to zero hit protection die.

## Zero Hit Protection

When damage reduces heretic's hit protection to zero or below, the heretic marks an **omen** and rolls 1d6 + omens. On a 10 or higher, the heretic will **die**. On a 9 and below, refer to the omens table. 

### Omens

Determine the result of the omen roll based on the table below.

> Note: If a heretic is already at zero or negative hit protection, any subsequent hit results in another omen taken and another omen roll (1d6 + omens). A heretic not staying down and choosing to fight on at negative hit points, despite the disadvantages, takes a significant risk of suffering more damage and potentially dying.

The table below describes the result of the damage in vague terms along with mechanical impacts. As a referee, describe injuries to the comfort level of your table.

Note that some of these results may require intervention to prevent death.

Injuries should inflict penalties that make sense in the fiction. For example, a treatable leg injury should impede movement. Trying to use the injured body part should impose disadvantage on a roll.

| 1d6 + omens | Result                                                     | Ripping                                                                        | Blunt                                                                         | Shocking                                                                                          | Caustic                                                  | Toxic                                                                           |
| ----------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------- |
| 15          | Luck Pushed: Grisly and instant death                      | Luck Pushed                                                                    | Luck Pushed                                                                   | Luck Pushed                                                                                       | Luck Pushed                                              | Luck Pushed                                                                     |
| 10-14       | Last Stand: Death in 1 round. Final action is at advantage | Last Stand                                                                     | Last Stand                                                                    | Last Stand                                                                                        | Last Stand                                               | Last Stand                                                                      |
| 8-9         | Bleeding out: Dying in 1d4 rounds without intervention     | Wounded + Severance + Bleeding Out                                             | Shattered Bone + Blunt Trauma + Bleeding Out                                  | Dazed + Organ Trauma + Bleeding Out                                                               | Lung Damage + Burned + Bleeding Out                      | Ill + Compromised Immunity + Bleeding Out                                       |
| 5-7         | Never the same again: 1d4 permanent injury                 | Wounded + Severance: Lose a body part, 1d4: 1: arm; 2: leg; 3: eye; 4: fingers | Shattered Bone + Blunt Trauma: -1d4 to dex                                    | Dazed + Organ Trauma: -1d4 to wil                                                                 | Lung Damage + Burned: -1d4 to str                        | Ill + Compromised Immunity: All saves versus toxins permanently at disadvantage |
| 2-4         | But a scratch: 1d4 downtime cycles to recover              | Wounded: Half movement and disadvantage on all actions until recovered         | Shattered Bone: Half movement and disadvantage on all actions until recovered | Dazed: Half movement and disadvantage on all actions until recovered, in and out of consciousness | Lung Damage: Disadvantage on all actions until recovered | Ill: Half movement and disadvantage on all actions until recovered              |

Omens cannot be removed. At 9 omens, death is inevitable.

> Note: The **Bleeding out** result includes the effects of the **Never the same again** result, which also includes the effects of the **But a scratch** result. **Last stand** and **Luck pushed** do not include the other results.

## Environmental Damage

- Non-magical fire (Caustic), 1d6
- On fire (Caustic), 2d6 damage per round
- Lava (Caustic), instant death
- Acid (Caustic), 1d6 damage 
- Drowning (Shocking)
	- After 3 + str rounds of holding breath, drop to zero hit protection
- Freezing water (Shocking), 1 HP per round until warmed
- Non-magical lightning (Shocking), 3d6 damage **and** mark 1 omen (does not force an omen roll)
- Falling (Blunt), 1d6 damage per 10 feet, to a maximum 10d6
- Rocks falling (Blunt), 3d6 damage
- Poison (Toxic), damage amount depends on the poison

## Ambush damage

If a player character is ambushed, the damage dice are doubled.

## Conditions

Some attacks inflict a condition. The following list is non-exhaustive and some monsters and environments may have special effects inflicting unique conditions.

- Exhausted: Disadvantage on all rolls
- Paralyzed: Unable to make any movement
- Grappled: Speed is 0, disadvantage on all rolls except to break the grapple
- Charmed: Must act friendly towards the charming creature
- Blind: Unable to see
- Deafened: Unable to hear
- Stunned: Unable to make significant movements
- Poisoned: Disadvantage on all actions

## Stabilizing 

An ally may try to stabilize a heretic who is **bleeding out** by rolling an ability check, casting a spell, using herbs, or some other manner of healing. 

### Death 

When a heretic dies, write down their fate on the back of the character sheet. The character sheet may be ritualistically burned, buried, or sent off in a funeral boat *later* because the player should roll up another heretic (or ideally have another heretic waiting in the wings) to get back into the game.

### Convalescing

Make note of any injury from the [omens](#Omens) table. All heretics who have gone below zero hit protection and been stabilized must rest. Heretics are recovered after a number of [downtime cycles](downtimecycle#Convalescing) rolled on the omens table.

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

- **Hunger**. If the player characters do not eat in a day, they may not heal after their rests.
- **Sleep deprivation**. After a night of not sleeping, characters must roll at disadvantage until they rest. They do not heal from the rest. 
- **Thirst**. After one day of not drinking, player characters must roll at disadvantage until they drink.  They do not heal from the rest. After three days, they must make DC 15 strength saves every hour or die. 