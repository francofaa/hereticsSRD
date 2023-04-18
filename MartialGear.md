---
title: Martial Gear
layout: default
permalink: /MartialGear
parent: Accessories
nav_order: 3
---

{% include toc.html %}

# Martial Gear

Armor, shields, and weapons have additional rules and specific costs whereas most common gear can be assumed to cost 1d10 (5) coins. 

## Armor

Armor augments armored defense. ad+n means that the armor augments the armored defense stat while ad=n means that the armored defense is set equal to that number without the dexterity bonus. 

Note that full plate and half plate assume that mail and gambesons may be part of the armored outfit. The armors denoted with *body* cannot be worn at the same time. This means that shields and helmets may augment ad=*n* suits of armor. A character wearing a shield, helmet, and full plate, for example, would have an armored defense of 18.

| armor                          | bonus | slots | placement   | cost  |
| ------------------------------ | ----- | ----- | ----------- | ----- |
| shield                         | +1    | 1     | 1h (1 hand) | 40    |
| helmet                         | +1    | 1     | head        | 40    |
| gambeson, padding, cloth armor | +1    | 1     | body        | 60    |
| brigandine, lamellar           | +2    | 1     | body        | 500   |
| mail                           | +3    | 2     | body        | 1,200 |
| half plate                     | =15   | 3     | body        | 4,000 |
| full plate                     | =16   | 4     | body        | 8,000 |

### Sundering Shields
When a character is hit by a melee or missile attack and they carry a shield, they may choose to destroy the shield in order to avoid all damage.

## Weapons

| weapon            | dmg  | slots | hands    | cost | tags                                         | dmg type                        |
| ----------------- | ---- | ----- | -------- | ---- | -------------------------------------------- | ------------------------------- |
| unarmed strike    | =str | 0     | n/a      | n/a  |                                              | bludgeoning                     |
| scythe            | 1d8  | 2     | 2h       | 50   | shoving, sweeping                            | piercing, slashing              |
| crossbow          | 1d8  | 3     | 2h       | 500  | loading, armor-piercing, 4z                  | piercing                        |
| halberd, pole axe | 1d8  | 3     | 2h       | 100  | reach, double-edged, shoving                 | piercing, slashing, bludgeoning |
| battle axe        | 1d8  | 2     | 2h       | 100  | shoving, sweeping                            | slashing, bludgeoning           |
| long sword        | 1d8  | 2     | 2h       | 100  | parrying, sweeping                           | piercing, slashing              |
| war hammer        | 1d8  | 2     | 2h       | 100  | crushing, sweeping                           | bludgeoning                     |
| bow               | 1d6  | 2     | 2h       | 50   | 3z                                           | piercing                        |
| sling             | 1d6  | 1     | 1h       | 5    | concealable, 2z                              | bludgeoning                     |
| spear             | 1d6  | 1     | 1h or 2h | 50   | versatile, thrown (1z), reach (2h)           | piercing, bludgeoning           |
| hand axe          | 1d6  | 1     | 1h or 2h | 50   | versatile, thrown (1z), dual-wield           | slashing, bludgeoning           |
| short sword       | 1d6  | 1     | 1h or 2h | 50   | versatile, parrying                          | piercing, slashing              |
| pick axe          | 1d6  | 1     | 1h       | 5    |                                              | piercing                        |
| dagger            | 1d6  | 1     | 1h       | 50   | concealable, subtle, dual-wield, thrown (1z) | piercing, slashing              |
| mace, flail       | 1d6  | 1     | 1h or 2h | 50   | versatile, crushing, sweeping                | piercing, bludgeoning           |
| staff             | 1d4  | 1     | 1h or 2h | 5    | reach (2h), versatile                        | bludgeoning                     |
| cudgel            | 1d4  | 1     | 1h       | 5    |                                              | bludgeoning                     |

Improvised weapon attacks usually inflict 1d4 damage.

### Sundering Melee Attacks
On a melee attack that hits, a character may choose to destroy their weapon to inflict double dice damage.

### Tags

> n.b.: "On a 20 or higher that hits" does not mean a 20 on the die, but a total of 20 or higher. For example, a roll of 19 with a +2 bonus is a 21 and therefore, the tag is triggered. If the target has an armored defense of 22, however, this is not a hit and the tag is not triggered (and you are probably better off not fighting them).

On a tag trigger, if your weapon has multiple tags, choose one to trigger. 

- *Concealable*: Can be hidden on the body when searched
- *Subtle:* If an attack is done secretly, this inflicts 2 x weapon die damage
- *Versatile:* This weapon may be used with 2 hands.
- *2h:* Roll 2 weapon die and take the higher result. 
- *Shoving:* On a 20 or higher that hits, the attacker may choose to shove or trip the target.
- *Dual-wield:* Two of these weapons can be wielded at the same time. This does not grant an extra attack. On a 20 or higher that hits, the attacker may roll an additional weapon die. 
- *Parrying:* On a 20 or higher that hits, the attacker's armored defense is increased by their +str bonus the next time the attacker is attacked. 
- *Crushing:* On a 20 or higher that hits, the target's armored defense is reduced by the attacker's +str bonus the next time the target is attacked.
- *Double-edged:* On a 20 or higher that hits, the attacker may make another attack with the butt of the polearm, inflicting 1d4 damage.
- *Thrown:* This weapon can be thrown at the stated range.
- *Reach*: Only when this weapon is wielded in two hands, the wielder does not need to disengage to avoid opportunity attacks. 
   - The spear and staff only have the reach property when wielded with 2 hands even though they can also be wielded in 1 hand.
- *Loading*: Requires 1 round to reload.
- \#z: Range for a ranged or thrown weapon, in zones. Beyond this range, the attack is made at disadvantage. The attack may miss if it is too distant.
- *Sweeping*: When the attacker rolls maximum damage on a hit, they may roll another attack at an adjacent foe.
- *Armor-piercing:* Attacks made with this weapon ignore mundane, non-natural armor and hit the dexterity defense of the target rather than the armored def (adef).