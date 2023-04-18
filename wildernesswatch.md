---
title: Wilderness Watch
layout: default
permalink: /wildernesswatch
nav_order: 5
parent: Time Procedures
---

{% include toc.html %}

# Wilderness Watch

Traveling the wilderness is done in **watches**. Each watch represents about a sixth of the day (4 hours). 

There are 6 **watches** in a day (about 3 in the day and 3 in the night, depending on season and latitude).

When a party is in the wilderness (whether entering or already in the wilderness), follow the wilderness watch procedure: 

1. *If it is the first watch of the day:* [Weather](#weather)
2. Resolve [Actions](#actions). Traveling is done as a party while character actions can be individually.
	- [Traveling](#traveling)
	- [Hunting and Foraging](#hunting-and-foraging)
	- [Camping](#camping)
	- [Harvesting Monster Parts](#harvesting-monster-parts)
3. [Wilderness Hazard Die](#wilderness-hazard-die) determines what happens during the watch

## Weather 

Weather is dependent on the season. Weather that is listed in **bold** is inclement weather.

**Traveling, foraging, harvesting, and hunting** done during inclement weather requires the character to make a +str save of DC 15 during that watch or suffer 1 point of damage. Additionally travel in inclement weather is made at half-speed.

| 2d6  | Spring           | Summer            | Autumn          | Winter          | Dry              | Wet           |
| ---- | ---------------- | ----------------- | --------------- | --------------- | ---------------- | ------------- |
| 2    | **Rain storm**   | **Thunder storm** | **Wild winds**  | **Snow storm**  | **Dust storms**  | **Monsoon**   |
| 3-5  | Drizzle          | **Very hot**      | **Heavy rains** | **Sleet**       | **Haze**         | **Rainstorm** |
| 6-8  | Overcast         | Clear, hot        | Cool            | **Bitter cold** | Clear, hot       | Drizzle       |
| 9-11 | Bright and sunny | Pleasantly sunny  | Patchy rain     | Overcast        | Beautifully warm | Patchy rain   |
| 12   | Clear and warm   | Beautifully warm  | Clear and crisp | Clear and crisp | Overcast         | Overcast      |

Any activity done in inclement weather has its DC increased by +3.

## Actions

The party may decide individually any course of actions. Note that travel should be done as a group, or the party will be split.

### Traveling

When traveling, the party should name a navigator. 

Characters move about 6 miles per watch, which is about double the distance to an object on the horizon.

Movement is halved through difficult terrain, in darkness, and in inclement weather. Movement is doubled when riding a mount or going solely by road. 

#### Forced March

Traveling longer than 3 watches requires a +str save of DC 15 per additional watch or suffer 1 point of damage per additional watch.

#### Navigation
Navigator determines direction and navigates. The referee secretly rolls that character's +int as necessary (determined by table below). If the characters have an accurate map, this is also not necessary:

| Navigation                                                            | DC       |
| --------------------------------------------------------------------- | -------- |
| Road, open sea with land in sight, grassland, coast, plains, farmland | No check |
| Arctic, desert, hills, open sea with clear skies                      | 10       |
| Forest, jungle, swamp, mountains, open sea with overcast skies        | 15       |
| Any region with **inclement weather**                                 | +3       |

##### Failed Navigation
On a failed navigation check, the referee should roll 1d10 in secret. 

| d10  | Direction               |
| ---- | ----------------------- |
| 1-4  | veered into left hex    |
| 5-6  | arrived in intended hex |
| 7-10 | veered into right hex   |

### Hunting and Foraging

When a player character decides to hunt or forage, they must make a +int check. Refer to the abundance table for DC's. 

Any of these activities done during **inclement weather** increases this DC by 3. A character performing activities in inclement weather must also make a +str save of DC 15 or suffer 1 point of damage.

Hunting for a specific animal or foraging for a specific component increases the DC by 2.

| Abundance                                   | DC  | Notes                              |
| ------------------------------------------- | --- | ---------------------------------- |
| Abundant food and water sources             | 10  |                                    |
| Limited food and water sources              | 15  |                                    |
| Very little, if any, water and food sources | 20  |                                    |
| Any region with **inclement weather**       | +3  | +str save vs 15 or suffer 1 damage |
| Specific component or animal                | +2  |                                    |


A quick reference table follows for each activity.


| Activity              | Restrictions                   | Yield                                 |
| --------------------- | ------------------------------ | ------------------------------------- |
| Hunting               | Spend 1 half of max ammo       | 2d4 + int food, trophy                |
| Forage for food       |                                | 1d4 + int food                        |
| Gather supply         |                                | 1d4 + int bonus / up to int def total |
| Craft ammo            |                                | 1d4 + dex bonus / up to dex def total |
| Forage for components | Requires at least +1 int bonus | 1d4 + int bonus (of 1d12 component)   |



#### Hunting

Hunting an animal requires a +int check plus spending one half of maximum [ammo](Inventory#ammo). If hunting a specific animal, +2 to the DC.

A successful roll yields 2d4 + int worth of food and a trophy, if applicable. Food is maximum 5 per slot. 

On a failure, finding the animal once again requires the character to spend another watch (no +int check required) and to spend the remainder of their ammo. Otherwise, the animal is lost.

#### Food

Foraging for food requires a +int check.

A successful roll yields 1d4 + int worth of food. Food is maximum 5 per slot. 

#### Supply and Ammo

Gathering supply requires a +int check.

A character may forage for 1d4 + int [Supply](Inventory#supply), up to a number equal to their intelligence defense. Note that supply is not tracked by slot. 

#### Ammo

Crafting ammo requires a +int check.

A character may forage for 1d4 +dex [Ammo](Inventory#ammo), up to a number equal to their dexterity defense. Note that ammo is not tracked by slot. 

#### Components 

Foraging for components to make [Medicinals](Medicinals) requires a +int check, but the player rolling must have at least a +1 int bonus. If searching for a specific component, +2 to the DC.

A successful roll yields 1d4 of a component determined by a d12 roll on the table below. If it would not make sense for a component to exist in an environment, the player should roll again. Each component is maximum 5 per slot. 


| Result | Herb, Fungus (1d4/5) | Appearance and properties                                          |
| ------ | -------------------- | ------------------------------------------------------------------ |
| 1      | Salt                 | Salt. Cures meat                                                   |
| 2      | Warynettle           | Spiky seed. Sleep inducing                                         |
| 3      | Heartsbane (fungus)  | Red powdery fungus. Blood coagulant, toxic                         |
| 4      | Sightleaf            | Leafy green herb. Heightens sight                                  |
| 5      | Sarnis hip           | Pink and orange arcing petals, flower. Anti-inflammatory           |
| 6      | Lionspaw             | Leafy green herb. Anti-inflammatory                                |
| 7      | Feverfew             | White petal flower. Reduces fever                                  |
| 8      | Honeyfoil            | Broad green leafy herb, orange pistils. Expectorant                |
| 9      | Devilsgrace (fungus) | Purple mushroom cap, secreting black liquid. Sleep-inducing, toxic |
| 10     | Starcomb             | Brown conical seed. Heightens all senses                           |
| 11     | Quick weed           | Black and green leafy plant. Heartening, heightens senses          |
| 12     | Flint moss           | Dry stringy moss. Flammable                                        |

### Camping 

Camping may require an alert member keeping watch. A safe short rest of one hour restores L x d8 HP (limited to once per watch) while a long rest of 8 hours (2 watches) in the wilderness with a meal restores 100% HP.

During camping, characters may also perform other tasks besides resting, such as curing game for rations, darning socks, crafting [medicinals](Medicinals), or performing rituals. 

### Harvesting Monster Parts

Monster parts may also be used to craft items, in coordination with the referee and may require appropriate checks. Intelligence check against a DC equal to 10 + monster HD may be appropriate for harvesting. Harvesting requires knowledge and care when extracting things like venoms, horns, teeth, digestive acids, and so on. 

## Wilderness Hazard Die 

At the end of every watch, roll 1d6. 

| d6  | Result                                                                                                                                                                     |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Encounter. Creature is far in locations with obstructed lines of sight, distant on flat terrains. Determined by the hex's encounter tables. Refer also to vibe check table |
| 2   | Fatigue. Each character suffers 1 point of damage unless they rest on the next watch. Ignore while [Camping](#camping).                                                    |
| 3   | Signs. Characters find signs of an encounter (based on encounter tables and environment).                                                                                  |
| 4   | Weather. Roll again on the [Weather](#weather) table.                                                                                                                      |
| 5   | Depletion. Each character rolls 1d10 + 10 and loses the item in that slot. They must spend the next watch recovering it. Ignore while [Camping](#camping).                 |
| 6   | Free. Nothing happens, or a keyed location is found.                                                                                                                       |

### Encounter Vibe Check

When rolling a hex's encounter, roll on the below table to determine the disposition of the creatures in the hex. Modify when necessary or when an alternative would be more interesting. 


| d12 | Activity / Desire             | d10 | Complication          |
| --- | ----------------------------- | --- | --------------------- |
| 1   | Hunting / Looking for Prey    | 1   | Hungry                |
| 2   | Patrolling / Scouting         | 2   | Sick / Young          |
| 3   | Scavenging / Looting          | 3   | Lost                  |
| 4   | Hiding                        | 4   | Arrested / Trapped    |
| 5   | Resting / Sleeping            | 5   | Disgruntled           |
| 6   | Working / Task                | 6   | Broken Gear / Injured |
| 7   | Meeting / Planning / Scheming | 7   | Fleeing               |
| 8   | Ritual / Ceremony             | 8   | Insane                |
| 9   | Art / Performance             | 9   | Dead                  |
| 10  | Setting Trap                  | 10  | *Roll NPC*            |
| 11  | Celebrating                   |     |                       |
| 12  | Eating                        |     |                       |

Disposition can be determined with a 2d6 roll: 

| 2d6   | Disposition  |
| ----- | ------------ |
| 2-3   | Hostile      |
| 4-5   | Unfriendly   |
| 6-8   | Uninterested |
| 9-10  | Polite       |
| 11-12 | Friendly     |

Encounters may result in [combat](combatround).