---
title: Character Creation
layout: default
permalink: /charactercreation
nav_order: 1
parent: Character
---
{% include toc.html %}

# Character Creation

When a player is creating a heretic, follow the character creation procedure to generate

1. [Ability Scores](#Ability%20Scores)
2. [Secondary Attributes](#Secondary%20Attributes)
3. [Hit Protection](#Hit%20Protection)
4. [Gear](#Gear)
5. [Traits](#Traits)
6. [Name](#Name)
7. [Languages](#Languages)

These steps are described in more detail below. 

For character sheets:
- Printable gridded PDF: [heretics_playerSheets_0-1-single-page-grids.pdf](heretics_playerSheets_0-1-single-page-grids.pdf)
- Google Spreadsheet (make a copy): [Sheets Link](https://docs.google.com/spreadsheets/d/19pv8S7_A3jCTb1wBprDFFxTAvuviTkqlpf4fHKd4JQE/edit#gid=0)
- Loose leaf paper should also suffice, there's not a ton of stuff to write down

> There are also alternative [level zero start](levelzerostart) procedures.

After the party is created, the players should work with the referee to generate their [Source](Source), the otherworldly entity that grants them access to magic and power. 

## Ability Scores

Character abilities are 

1. Strength
2. Dexterity
3. Willpower
4. Intelligence

All ability bonuses start at 0. Add 10 to get that ability's defense. For example, a strength bonus of +2 is a strength defense of 12. 

Roll 1d4 three times. Each time, add +1 to an ability according to its order above. 1=Strength, 2=Dexterity, 3=Willpower, 4=Intelligence. 

Then roll 1d4 once. *Subtract* 1 from the ability that is rolled. 

You may then swap 2 ability bonus scores.

For example: The first d4 lands on a 4, so Intelligence is increased by 1. The second lands on a 3, so Willpower increases by 1. The third lands on 4 again, so Intelligence is increased by 1. The last lands on 1, so Strength is *decreased* by 1. The array ends with Strength=-1, Dexterity=0, Willpower=1, Intelligence=2.

Possible starting arrays, not taking into account position of abilities, are as follows.

1. 3, 0, 0, -1
2. 2, 1, 0, -1
3. 1, 1, 1, -1
4. 2, 0, 0, 0
5. 1, 1, 0, 0

Refer to [Abilities](Abilities) for more information.

## Secondary Attributes

Your secondary abilities are derived as follows:

- From Strength
	- Maximum inventory = defense score 
- From Dexterity
	- Armored defense = defense score, plus any armor
	- Maximum ammo = defense score (start with all of your ammo)
- From Willpower
	- Mana Dice = bonus score 
	- Maximum retainers = bonus score
	- Warded defense = defense score, plus any wards
- From Intelligence
	- Maximum supply = defense score (start with all of your supply)


Movement is 40 feet of combat movement and 120 feet of exploration movement.

Omens start at 0.

## Hit Protection 

Roll 1d8 to find your hit protection. You may also roll 1d8 rerolling 1's and 2's or 2d4.

Refer to [Damage](Damage) for more on hit protection.

## Gear

Roll 1d4, 1d6, 1d8, 2d10 (10's and 1's places), 1d12, and 1d20 or choose from the lists below to determine the gear for your character. If there are blanks, the character receives nothing. 

| d4  | Magical Gear                          | Requirement     |
| --- | ------------------------------------- | --------------- |
| 1   |                                       |                 |
| 2   | 1 [medicinal](Medicinals) 5/5 (d10)                 | 1 slot          |
| 3   | 1 wd+1 [ward](magicalitems#Wards)                           | +1 int, 1 slot  |
| 4   | 1 [spell](d100spells) (d100) & 1 [focus](magicalitems#Focuses) (1 mana die) | +1 int, 2 slots |

Roll 1d8 and 1d6 and cross reference the numbers to find your background. You get all the gear from your background. Each piece of gear takes up one slot.

You start with 1 background which also informs what you start with on your person. These are failed professions, so treat them as such. 

> For non-human species, if they are allowed in the campaign, refer to the [other species](otherspecies). This may replace or supplement your background. Consult with your referee before doing this.

Actions performed using skills or tools relevant to a heretic's background may not require a roll to resolve or may be given some bonus based on the referee's discretion.

| d8/d6 | 1                                                       | 2                                                            | 3                                                               | 4                                                                | 5                                                                      | 6                                                       |
| ----- | ------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------- |
| 1     | Miner: pickaxe, lantern, 50 feet of rope                | Monastic: ink and quill, mini barrel of ale, prayer book     | Farmer: scythe, eggs and bread (5/5 rations), thick gloves      | Gravedigger: shovel, lantern, bucket                             | Executioner: great axe, hood, manacles                                 | Carpenter: hammer, handsaw, bag of nails                |
| 2     | Bandit: dagger, 50 feet of rope, mask                   | Beekeeper: jar of honey, smoke bomb, net                     | Clergy: holy symbol, censor, prayer book                        | Trash collector: 10 foot pole with hook, lantern, bucket         | Barber-surgeon: scissors, handsaw, bandages                            | Minstrel: musical instrument, perfume, disguise kit     |
| 3     | Lumberjack: hand axe, rope, firewood                    | Shepherd: 10 foot pole, whistle, sling 1d4 20/40             | Mercenary: short sword, shield, 3d8 coins (in foreign currency) | Fence: false documents, sealing wax, metal file                  | Burglar: grappling hook, 50 feet of rope, lockpicking tools            | Brewer: mini-keg of ale, jar of yeast, empty growler      |
| 4     | Hunter: bow, quiver of arrows, tent                     | Fisher: fishing rod, net, spear                              | Bureaucrat: ink and quill, official stamp (stolen), sealing wax | Smuggler: disguise kit, false documents, 10 foot pole            | Diviner: divining cards or bones, tea leaves, telescope                | Baker: rolling pin, bread 5/5 rations, bag of flour     |
| 5     | Hermit: 1 random medicinal 5/5, staff, 2 stakes         | Jester: Scepter, motley garb, cudgel                         | Puppeteer: puppet, spool of string 250', hammer                 | Candlemaker: candles 20/20, beeswax, spool of string (wick) 250' | Sailor: Spyglass, short sword, net                                     | Scribe: Lamp oil, quill and ink, 50 sheafs of parchment |
| 6     | Scavenger: scrap metal, 10 foot pole, lantern           | Surveyor: rope, compass, ink and quill                       | Debt collector: disguise kit, mace, manacles                    | Counterfeiter: false documents, ink and quill, sealing wax       | Street Performer: juggling items, disguise kit, 50 feet of rope        | Guard: shield, half plate, spear                        |
| 7     | Trader: valuable trinket, ink and quill, 2d6 x 10 coins | Tinker: grease, fine tools, scrap metal                      | Bounty-hunter: quiver of bolts, crossbow, dagger                | Cut-purse: dagger, disguise kit, ball bearings                   | Gambler: loaded dice or trick deck, mirror, 10 + 1d4! coin (exploding) | Apothecary: empty vials, antitoxin, shears              |
| 8     | Messenger: traveling papers, lantern, bedroll           | Hedge witch: fetish wd+1, 1 medicinal 5/5, mortar and pestle | Pit-fighter: cudgel, gambeson, net                              | Alchemist: potion brewing kit, ink and quill, antitoxin          | Blacksmith: hammer, metal file, bellows                                | Scholar: ink and quill, blank book, sealing wax         |

[Shields and helmets](MartialGear#Armor) add +1 to armored defense (ad).

| d10 | Armor           | Slots Required |
| --- | --------------- | -------------- |
| 1   |                 |                |
| 2   |                 |                |
| 3   |                 |                |
| 4   |                 |                |
| 5   |                 |                |
| 6   | shield          | 1              |
| 7   | shield          | 1              |
| 8   | helmet          | 1              |
| 9   | helmet          | 1              |
| 10  | helmet & shield | 2              |

[Armor](MartialGear#Armor) augments armored defense (ad). 

| d00 | Armor                       | Slots Required | Armored Defense Bonus |
| --- | --------------------------- | -------------- | --------------------- |
| 10  |                             |                |                       |
| 20  |                             |                |                       |
| 30  |                             |                |                       |
| 40  |                             |                |                       |
| 50  |                             |                |                       |
| 60  | gambeson, padding, or cloth | 1              | +1                    |
| 70  | gambeson, padding, or cloth | 1              | +1                    |
| 80  | brigandine or lamellar      | 1              | +2                    |
| 90  | brigandine or lamellar      | 1              | +2                    |
| 00  | mail                        | 2              | +3                    |

[Weapons](MartialGear#Weapons) have damage die, tags, and damage types. 

| d12 | Weapons             | Slots Required | Damage | Hands    | Tags                                             | Damage Type          |
| --- | ------------------- | -------------- | ------ | -------- | ------------------------------------------------ | -------------------- |
| 1   |                     |                |        |          |                                                  |                      |
| 2   | cudgel              | 1              | d4     | 1h       |                                                  | bludg                |
| 3   | dagger              | 1              | d4     | 1h       | concealable, subtle, dual-wield, thrown (20/60r) | pierce, slash        |
| 4   | staff               | 1              | d6     | 1h or 2h | versatile, reach (2h)                            | bludg                |
| 5   | short sword         | 2              | d6     | 1h or 2h | versatile, parrying                              | pierce, slash        |
| 6   | hand axe            | 2              | d6     | 1h or 2h | versatile, thrown (20/60r), dual-wield           | slash, bludg         |
| 7   | spear               | 2              | d6     | 1h or 2h | versatile, thrown (20/60r), reach (2h)           | pierce, bludg        |
| 8   | bow                 | 2              | d6     | 2h       | 150/600r                                         | pierce               |
| 9   | sling               | 1              | d6     | 1h       | concealable, 60/240r                             | bludg                |
| 10  | crossbow            | 2              | d8     | 2h       | loading (1r), 300/1200r                          | pierce               |
| 11  | mace or flail       | 2              | d6     | 1h or 2h | versatile, crushing, sweeping                    | pierce, bludg        |
| 12  | pole axe or halberd | 3              | d8     | 2h       | reach, double-edged, shoving                     | pierce, bludg, slash |



| d20 | Adventuring Gear             | Slots Required |
| --- | ---------------------------- | -------------- |
| 1   | rations 5/5                  | 1              |
| 2   | rope 50 feet                 | 1              |
| 3   | torches 3/3                  | 1              |
| 4   | grappling hook               | 1              |
| 5   | tent                         | 1              |
| 6   | lantern; lantern oil 2/2     | 2              |
| 7   | chalk 10/10                  | 1              |
| 8   | pole 10 feet                 | 1              |
| 9   | chain 10 feet                | 1              |
| 10  | crowbar                      | 1              |
| 11  | candles 10/10                | 1              |
| 12  | caltrops 10/10               | 1              |
| 13  | grease 10/10                 | 1              |
| 14  | rope 50 feet; grappling hook | 2              |
| 15  | net                          | 1              |
| 16  | shovel                       | 1              |
| 17  | bucket                       | 1              |
| 18  | stakes 3/3; mallet           | 2              |
| 19  | flask                        | 1              |
| 20  | 3d6 x 10 coins               | 1              |

## Traits

Roll 1d4, 1d6, 1d8, 2d10 (10's and 1's places), 1d12, and 1d20 or choose from the lists below to determine the character traits and relationships for your character. 

| d4  | Age                 |
| --- | ------------------- |
| 1   | Teenaged or elderly |
| 2   | Young adult         |
| 3   | Mature prime        |
| 4   | Middle-aged         |


| d6 | Clothes     |
| --- | ----------- |
| 1   | Uniform     |
| 2   | Eccentric   |
| 3   | Formal      |
| 4   | Fashionable |
| 5   | Foreign     |
| 6   | Ceremonial  |

| d8  | Speech     |
| --- | ---------- |
| 1   | Squeaky    |
| 2   | Booming    |
| 3   | Formal     |
| 4   | Hoarse     |
| 5   | Whispery   |
| 6   | Drawling   |
| 7   | Rapid-fire |
| 8   | Monotone   |



| d10 | Vice              |
| --- | ----------------- |
| 1   | Resentful         |
| 2   | Vengeful          |
| 3   | Rude              |
| 4   | Greedy            |
| 5   | Arrogant          |
| 6   | Deceitful         |
| 7   | Reckless          |
| 8   | Vain              |
| 9   | Bitter            |
| 10  | Aggressive        |

| d00 | Virtue      |
| --- | ----------- |
| 10   | Ambitious   |
| 20   | Cautious    |
| 30   | Disciplined |
| 40   | Serene      |
| 50   | Generous    |
| 60   | Humble      |
| 70   | Honest      |
| 80   | Loyal       |
| 90   | Courageous  |
| 00  | Merciful    |


| d12 | Misfortunes |
| --- | ----------- |
| 1   | Blackmailed |
| 2   | Cursed      |
| 3   | Defrauded   |
| 4   | Discredited |
| 5   | Disowned    |
| 6   | Exiled      |
| 7   | Framed      |
| 8   | Haunted     |
| 9   | Rejected    |
| 10  | Pursued     |
| 11  | Demoted     |
| 12  | None        |


| d20 | Connection to the Character on my Left    |
| --- | ----------------------------------------- |
| 1   | Blood relation                            |
| 2   | In-law                                    |
| 3   | Childhood friends                         |
| 4   | Carousing / drinking buddies              |
| 5   | Colleagues / Fellow enthusiasts           |
| 6   | Retrieved something for me I wanted       |
| 7   | Stopped me from doing something foolish   |
| 8   | Helped me escape                          |
| 9   | Saved my life                             |
| 10  | Helped me save face                       |
| 11  | Kept a secret for me                      |
| 12  | I owe them                                |
| 13  | Defended a friend of mine                 |
| 14  | We fought alongside each other            |
| 15  | I admire them for their skills            |
| 16  | Caught me committing a crime              |
| 17  | Former rivals                             |
| 18  | We fought on opposite sides of a conflict |
| 19  | Former customer                           |
| 20  | I lost a bet to them                      |

## Name

Choose or roll on a naming table. For the Isurholm setting, there is a [names table](namestables) available.

## Languages

Player characters start with as many **common languages** as they like as long as they are reasonable to have, with at least one designated as a mother tongue. Indicate speaker proficiency.

1. native or bilingual
2. conversational (paragraph level, unique language generation, tenses)
3. functional (sentence level, some unique language generation)
4. elementary (word level, parroting / memorizing phrases, no unique language generation)

Languages are not determined by species but by origin. There is no "common" language. It should be determined by the referee what is the most commonly spoken language of a particular region. 

Every initial +1 to intelligence can be spent on an **uncommon language**. 

### Common languages

- Distant: Languages of people that do not live here
- Trade: Pidgins and cants inherent to certain trades

### Uncommon languages

- Ancient: Old versions of the same languages
- Monster (costs 2): Languages of anything but humans and humanoid species, such as fey languages, merfolk languages, goblin languages, and so on. The language should be assumed to be a language of that particular region. For example, a merfolk living 1,000 miles away probably does not speak the same language as the merfolk who taught you. In fact, if deemed appropriate by the referee, a merfolk living downstream may speak a completely different language as well.
- Otherworldly (costs 3): Languages of creatures outside of this world
- Divine (costs 3): Languages of deities, including fiends


## Reading a Stat Line
All creatures can be expressed in a single stat line. 

1. L# or \#HD: Indicates level for a player character or retainer / hit dice for monsters
2. HP \#: Indicates hit protection. 
3. AD \# (*armor, if applicable*): Armored Defense stat, followed by any modifying armor pieces
4. WD \# (*wards, if applicable*): Warded Defense stat followed by any modifying wards. 
5. STR # DEX # WIL # INT #: The four ability in a row. Only lists the bonus. Add 10 to get the defense. When a stat line omits the ability, its bonus is 0. 
6. MV # (#): Movement, in feet. The first number is exploration (10 minutes in a dungeon), second number combat movement (10 seconds). Usually omitted if it is 120 (40).
7. Att: Attacks, usually followed by a to-hit bonus, a die (damage), and a parenthetical indicating the weapon, or spell. 
8. Items: List of all items that the creature carries. 
9. *Special ability*: Any additional abilities. [Boons](Boons) can appear here. Monsters have their abilities here as well. 

**Example:** 

Ogden Dankworth. L2. HP 13. AD 13 (shield, helmet). WD 11 (haunted doll). STR 2 DEX 1 INT 1. Att 1 x 1d6 (short sword). Items: crowbar, rope, short sword 1d6, shield ad+1, helmet ad+1, fireball (spellbook), haunted doll md+1. Butcher: When you kill an enemy, you may immediately make another attack

Mind Vampire. 5HD. AD 15. MD 15. Str 5, Int 7, Wil 5. Att 1 x +5 2d8 grappling, or psychic shock, or drain will. Psychic shock: 30' radius, WD save 15 or incapacitated, 2 uses. Drain will: atk +5, 1 grappled target, drains -1d6 wil.
