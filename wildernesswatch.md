---
title: Wilderness Watch
layout: default
permalink: /wildernesswatch
nav_order: 4
parent: Procedures
---

{% include toc.html %}

# Wilderness Watch

Traveling the wilderness is done in **watches**. Each watch represents about four hours. 

There are 6 **watches** in a day (about 3 in the day and 3 in the night, depending on season and latitude).

When a party is in the wilderness (whether entering or already in the wilderness), follow the wilderness watch procedure: 

1. *If it is the first watch of the day:* [Weather](#Weather)
2. Resolve [Actions](#Actions). Traveling is done as a party while character actions can be individually.
	- [Traveling](#Traveling)
	- [Hunting](#Hunting)
	- [Foraging](#Foraging)
	- [Camping](#Camping)
	- [Harvesting Monster Parts](#Harvesting%20Monster%20Parts)
3. [Wilderness Hazard Die](#Wilderness%20Hazard%20Die) 

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

Characters move 6 miles per watch.

Movement is halved through difficult terrain, in darkness, and in inclement weather. Movement is doubled when riding a mount or going solely by road. 

#### Forced March
Traveling longer than 3 watches (12 hours) requires a +str save of DC 15 per additional watch or suffer 1 point of damage.

#### Navigation
Navigator determines direction and navigates. The referee secretly rolls that character's +int as necessary (determined by table below). If the characters have an accurate map, this is also not necessary:

| Navigation                                                     | DC       |
| -------------------------------------------------------------- | -------- |
| Road, open sea with land in sight                              | No check |
| Grassland, coast, plains, farmland                             | 5 or no check       |
| Arctic, desert, hills, open sea with clear skies               | 10       |
| Forest, jungle, swamp, mountains, open sea with overcast skies | 15       |
| Any region with **inclement weather**                        | +3       |

##### Failed Navigation
On a failed navigation check, the referee should roll 1d10 in secret. 

| d10  | Direction               |
| ---- | ----------------------- |
| 1-4  | veered into left hex    |
| 5-6  | arrived in intended hex |
| 7-10 | veered into right hex   |

### Hunting

Characters spend time hunting down an animal. This requires a +int check of DC 15 and spending one half of current [ammo](Ammo). 

Hunting during **inclement weather** increases this DC by 3 (to 18). The character must also make a +str save of DC 15 or suffer 1 point of damage.

On a success, yield 1d6 rations and a trophy, if applicable. On a failure, finding the animal once again requires the character to spend another watch (no +int check required) and to spend the remainder of their ammo. Otherwise, the animal is lost.

### Foraging  

Characters may forage for food, supply, ammo, or components. This requires a +int check. Such a check may also be impossible in certain environments or under certain weather conditions.

Foraging done during **inclement weather** increases this DC by 3 (to 18). The character must also make a  +str save of DC 15 or suffer 1 point of damage.

#### Food

The DC is based on the environment.

| Foraging                                    | DC  |
| ------------------------------------------- | --- |
| Abundant food and water sources             | 10  |
| Limited food and water sources              | 15  |
| Very little, if any, water and food sources | 20  |
| Any region with **inclement weather**       | +3  |

A successful roll yields 1d4 worth of food. Food is maximum 5 per slot. 

#### Supply and Ammo

Foraging for supply or ammo requires a +int check of DC 15. Foraging during **inclement weather** increases this DC by +3 (to 18).

A character may forage for 1d4 + int [Supply](Inventory#Supply) once per day, up to a number equal to their intelligence defense. Note that supply is not tracked by slot. 

A character may forage for 1d4 +dex [Supply](Inventory#Supply) once per day, up to a number equal to their dexterity defense. Note that ammo is not tracked by slot. 

#### Components 

Components can be used to make [Medicinals](Medicinals).

The DC is based on the environment.

| Foraging                                    | DC  |
| ------------------------------------------- | --- |
| Abundant food and water sources             | 10  |
| Limited food and water sources              | 15  |
| Very little, if any, water and food sources | 20  |
| Any region with **inclement weather**       | +3  |

A successful roll yields 1d4 of each component. 

The character rolls d12 per intelligence bonus point they have. A character with 0 or negative intelligence bonus cannot forage for components. 

If it would not make sense for a component to exist in an environment, the player should roll again.

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

For example, a character with +3 intelligence rolls +int and beats the DC of 10. This yields 3d4 components. The component is determined from the d12 table above. The player rolls a 6, 8, 8. They get 1d4 lionspaw and 2d4 honeyfoil.

Each component is maximum 5 per slot. 

### Camping 

Camping may require an alert member keeping watch. A safe short rest of one hour restores L x d8 while a long rest of 8 hours (2 watches) in the wilderness with a meal restores 100% HP.

### Harvesting Monster Parts

Monster parts may also be used to craft items, in coordination with the referee and may require appropriate checks. Intelligence check against a DC equal to 10 + monster HD may be appropriate for harvesting. Harvesting requires knowledge and care when extracting things like venoms, horns, teeth, digestive acids, and so on. 

## Wilderness Hazard Die 

At the end of every watch, roll 1d6. 

| d6  | Result                                                                                                                                                                                   |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Encounter. 2d6 x 10 feet away in locations with obstructed lines of sight, 2d6 x 40 feet away on flat terrains. Determined by the hex's encounter tables. Refer also to vibe check table |
| 2   | Fatigue. Each character suffers 1 point of damage unless they rest on the next watch. Ignore while [Camping](#Camping).                                                           |
| 3   | Signs. Characters find signs of an encounter (based on encounter tables and environment).                                                                                                |
| 4   | Weather. Roll again on the [Weather](#Weather) table.                                                                                                                                    |
| 5   | Depletion. Each character rolls 1d10 + 10 and loses the item in that slot. They must spend the next watch recovering it. Ignore while [Camping](#Camping).                               |
| 6   | Free. Nothing happens, or a keyed location is found.                                                                                                                                           |

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