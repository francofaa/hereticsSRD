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

Damage that reduces character's hit protection to zero lowers a character's strength defense by the amount remaining. Any actions that a character takes while under 0 hit protection are done at disadvantage. 

Any damage that takes the character to 0 strength defense kills them outright. 

Characters at or below 0 hit protection are considered to be **dying**. 

NPCs that are lowered to zero hit protection die.

## Direct Damage
Some damage may bypass hit protection. Some damage may also outright kill a character. 

### Environmental

All of the following environmental damage (*in its non-magical form*) is considered **direct damage** to strength defense:

- Non-magical fire, 1d6 direct damage
- On fire, 2d6 direct damage per round
- Lava, instant death
- Acid, 1d6 direct damage
- Drowning. Characters can hold their breath for 30 seconds (3 rounds of combat) per point of Strength bonus. After this point, they must make strength saving throws DC 15 every round or die. 
- Freezing water. Characters must make Strength saving throws DC 15 every minute or take 1 direct damage.
- Non-magical lightning, 3d6 direct damage
- Falling, 1d6 direct damage per 10 feet, to a maximum 10d6.
- Poison, direct damage (amount depends on the poison) 

### Ambush damage

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

## Stabilizing 

When a character is reduced to zero hit protection, they must be stabilized within an hour or else they **die**.

An ally may try to stabilize the downed character by rolling an ability check, casting a spell, using herbs, or some other manner of healing. 

If such an action would restore hit protection, It instead stabilizes the character.

Once stabilized, the character's strength defense is restored to full. The character then rolls 1d20 on the injury table: 

1: False hope: you're dead
2: Lose a body part
3-6: Feeble: lose 1d6 str 
7-10: Shaky: lose 1d6 dex 
11-14: Addled: lose 1d6 int
15-18: Weak: lose 1d6 wil
19: Disadvantage on all checks until rested
20: Standing: Instantly heal to 1d8 hit protection

Unless a 1 was rolled, the character heals to 1 hit protection.

### Death 

When a character dies, write down their fate on the back of the character sheet. The character sheet may be ritualistically burned, buried, or sent off in a funeral boat *later* because the player should roll up another character (or ideally have another character waiting in the wings) to get back into the game.

### Convalescing

The injuries feeble, shaky, addled, and weak are removed after a number of [downtime cycles](downtimecycle.md#Convalescing) equal to the lowest result of Ld6. For example, a level 4 character rolls 4d6, resulting in a 3, 3, 5, and 6. The lowest number is 3, so the character's ability is restored after 3 downtime cycles.


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