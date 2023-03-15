---
title: Monsters
layout: default
permalink: /monsters
nav_order: 1
parent: Referee Tools
---

{% include toc.html %}

# Monsters


A monster's threat level is measured by their hit dice (HD). Hit dice are always d8. When a monster is reduced to 0 hit protection, they are dead (contrast with [damage](Damage) to player characters), unless a player character wishes to inflict non-deadly incapacitating damage. 

## Monster Creation Procedure

These can be done in any order. 

1. Roll 1d20 on the [Monster Threat Table](#Monster%20Threat%20Table) to determine the threat level. 
2. Roll 1d8 on the [Monster Type](#Monster%20Type) table to determine the strategies, strengths, and weaknesses.
3. Roll 1d12 as many times as is desired on the [Monster Abilities](#Monster%20Abilities) table to determine special abilities.
4. Roll 2d4 on the [Monster Motivations](#Monster%20Motivations) to determine the monster's motivations, if they are a leader (or a lone actor).


### Monster Conversion  

Monsters can be pulled from any B/X derivation with little modification for Heretics. 

Saving throws in Heretics work by rolling a d20 plus a relevant stat rather than rolling under a number for a particular type of save. Therefore, saving throws will be the most different thing. Refer to the Monster Threat Table for translating strong and weak saving throws. Consider what a monster might be good and bad at and use that to modify the d20 roll. 

## Monster Threat Table 

The dmg avg column refers to total damage across all attacks. 

Strong stat, weak stat, and average stat refers to the monster's ability scores based on their monster type. These are used for their saving throws. 

In the To Hit column, the larger number (if there is one) should apply to monsters of the following categories: Brutes, Predators, Snipers, and Soldiers.

| HD  | HP avg | To Hit | strong stat | weak stat | avg stat | d20 |
| --- | ------ | ------ | ----------- | --------- | -------- | --- |
| 1/4 | 1      | 0      | 1           | -3        | 0        | 1   |
| 1/2 | 2      | 0      | 1           | -3        | 0        | 2   |
| 1   | 4      | 1      | 1           | -2        | 0        | 3   |
| 2   | 9      | 1,2    | 2           | 0         | 1        | 4   |
| 3   | 13     | 2,3    | 3           | 1         | 2        | 5   |
| 4   | 18     | 3,4    | 4           | 1         | 2        | 6   |
| 5   | 22     | 4,5    | 5           | 1         | 3        | 7   |
| 6   | 27     | 5,6    | 6           | 2         | 3        | 8   |
| 7   | 31     | 6,7    | 7           | 2         | 4        | 9   |
| 8   | 36     | 7      | 8           | 2         | 4        | 10  |
| 9   | 40     | 7,8    | 8           | 3         | 5        | 11  |
| 10  | 45     | 8      | 9           | 3         | 5        | 12  |
| 11  | 49     | 8,9    | 10          | 4         | 6        | 13  |
| 12  | 54     | 9      | 10          | 4         | 6        | 14  |
| 13  | 58     | 9,10   | 11          | 4         | 6        | 15  |
| 14  | 63     | 10     | 12          | 5         | 7        | 16  |
| 15  | 67     | 10,11  | 12          | 5         | 7        | 17  |
| 16  | 72     | 11     | 13          | 5         | 7        | 18  |
| 17  | 76     | 11,12  | 14          | 6         | 8        | 19  |
| 18  | 81     | 12     | 14          | 6         | 8        | 20  |
| 19  | 85     | 12,13  | 14          | 6         | 9        |     |
| 20  | 90     | 13     | 15          | 7         | 10       |     |
| 21  | 94     | 14     | 16          | 8         | 10       |     |


## Monster Type

Monsters can be arranged by categories. These determine general strategies and strong and weak stats. 

Weaknesses can also include things like 

- environment
- conditions
- damage types
- interruptions to senses

Monsters can also have conditional immunities or cannot be truly defeated until certain conditions are met. For example, the ghost's ring has to be returned to its corpse before it can be destroyed. 



| d8  | Type        | Strong                                          | Weak                                       | Strategy                                  |
| --- | ----------- | ----------------------------------------------- | ------------------------------------------ | ----------------------------------------- |
| 1   | Brute       | str, adef, wdef, morale, resistances            | int, stealth, tactics, perception, tactics | intimidate, brute force, holding the line |
| 2   | Soldier     | str, attacking, morale, discipline and cohesion | int, magic, speed, stealth, no leader      | follow orders, protect the leader         |
| 3   | Predator    | dex, attacking, stealth, patience, scouting     | wil, resistances, morale, adef, wdef       | ambushes, hit and run, scouting, stalking |
| 4   | Sniper      | dex, perception, ranged attacking               | wil, melee, resistances, morale, adef      | staying hidden, ranged attacks            |
| 5   | Infiltrator | wil, deception, stealth                         | str, direct combat, wdef, adef             | lead targets into a trap, gather intel    |
| 6   | Leader      | wil, magic, wdef                                | str, direct combat, isolation, resistances | using minions, planning                   |
| 7   | Shaper      | int, environment control                        | str, melee, being stuck in one place       | control the environment, move constantly  |
| 8   | Support     | int, healing, morale, adef                      | dex, melee, speed                          | stay behind the line, buff and heal       |




## Monster Abilities

Consider **telegraphing** major attacks. For example, if a monster has a breath weapon, on the turn before, have them charge it up, rear its head back, allowing a ball of fire to form in its mouth. 

| d12 | Ability            | Effect                                                                                                                                                                                                              |
| --- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Pounce             | Movement in a straight line, attack forces str save or knocked prone.                                                                                                                                               |
| 2   | Ability drain      | Drain target ability by 1d6                                                                                                                                                                                         |
| 3   | Change environment | Terrain, weather, sensory, or magical alteration. As an action or a continuous aura                                                                                                                                 |
| 4   | Sphere             | Half on a save. 1d6 per HD in radius of 5 feet per HD. 1 use per 3 HD per fight                                                                                                                                     |
| 5   | Inflict condition  | Save or inflict grappled, paralyzed, deafened, blinded, stunned, charmed, poisoned etc. As an action or a continuous aura. This could also linger after battle or even target weapons or armor (like rusting them). |
| 6   | Breath             | Cone 10 feet per 2 HD, 1d6 per 2 HD.  1 use per 3 HD  per fight                                                                                                                                                     |
| 7   | Multi-attack       | 1 attack plus 1 extra attack per 3 HD (3 HD would have 2 attacks, 6 HD would have 3 attacks)                                                                                                                        |
| 8   | Resistance         | Half damage or immunity to certain damage types or weapons                                                                                                                                                          |
| 9   | Special Movement   | Flight, burrow, etherealness, extreme speed, spider climb, ignore difficult terrain, underwater, leap, teleport                                                                                                     |
| 10  | Shove              | Save or target (1 target per 2 HD) is moved 10 feet per 5 HD.                                                                                                                                                       |
| 11  | Conditional bonus  | Bonus to damage, to hit, to adef, to wdef, HP regeneration, or other stat under certain conditions (darkness, underwater, in a forest, if not damaged by fire etc)                                                  |
| 12  | Spell caster       | Casts a spell from the [spell list](d100spells)                                                                                                                                                                     |

Special monsters may also have other unique abilities, such as a teleporting strike, summoning other monsters, or a death curse. 

## Monster Motivations 

Consider what a monster (particularly a monster leader) would want. Consider the [faction](Factions) or branch of a faction that they may lead, if applicable. Even without a faction, monsters always have motivations. 


| d4  | Method                      | Target         |
| --- | --------------------------- | -------------- |
| 1   | Create / Establish / Summon | System         |
| 2   | Control                     | Object         |
| 3   | Destroy / Kill              | Person / Group |
| 4   | Steal / Rob                 | Place          |

For more specific ideas, the referee may consult the table below, which contains potential results of the rolls from the above table. 

| d8  | Trope     | Motivation combination                    |
| --- | --------- | ----------------------------------------- |
| 1   | Beast     | Run wild, destroy, kill people            |
| 2   | Summoner  | Bring forth, give birth                   |
| 3   | Collector | Steal specific objects or people          |
| 4   | Destroyer | Destroy a community                       |
| 5   | Parasite  | Infest, control, consume from a system    |
| 6   | Conqueror | Possess and control a place               |
| 7   | Tempter   | Control people and tempt them             |
| 8   | Judge     | Punish and kill those who they deem wrong |


## Additional Resources 

Since I do not manage these websites, they may rot, so be forewarned. 

- [Old School Essentials Bestiary](https://oldschoolessentials.necroticgnome.com/srd/index.php/Monster_Descriptions)
- [The Free Bestiary](https://clayadavis.gitlab.io/osr-bestiary/bestiary/)
- [donjon Monster Generator for Microlite](https://donjon.bin.sh/m20/monster/)
- [Knave Irish Monsters (Google Doc Link)](https://docs.google.com/document/d/1NhYdSyMUbVE-fmjIB4fk8ITbxwCf1EwH7ZHniOS0GrQ/edit#heading=h.g193jn9w9t94)
- [Highland Paranormal Society Knave Bestiary](https://natetreme.com/blog/2019/2/20/a-bestiary-for-knave)
- [Ford's Faeries](https://www.drivethrurpg.com/product/258394/Fords-Faeries-A-Bestiary-Inspired-by-Henry-Justice-Ford?term=fords)
- [CC1 Creature Compendium](https://www.drivethrurpg.com/product/147588/CC1-Creature-Compendium)
- [d50 Puzzle Monster Death Requirements](https://iceandruin.blogspot.com/2017/08/d50-puzzle-monster-death-requirements.html)