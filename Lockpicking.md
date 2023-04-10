---
title: Lockpicking
layout: default
permalink: /lockpicking
nav_order: 1
parent: Mechanical Procedures
---

{% include toc.html %}

# Lockpicking

To pick a lock, the character tries an action to unlock a tumbler. Every lock has three tumblers. The actions are:

- Tap (T)
- Probe (P)
- Rake (R)

## Qualities of Locks

1. Each lock has three tumblers, each of which which require an action. Additionally, no two sequential tumblers require the same action. 
2. Each lock type requires the same set of actions once it is solved. When a lock is solved, every other lock of that type is solved in the same manner. In this manner, the character gains expertise in lockpicking. 
3. Each lock has a durability score that acts like hit protection. At zero, the lock is broken off.

## Picking Procedure

A character chooses one of the three actions (tap, probe, rake) to unlock the tumblers of the lock. On a failure, the lock becomes stiff. On a subsequent success the lock is no longer stiff. 

A failure on a stiff lock results in the lock getting jammed. It must be broken off. To break a lock off, the character must inflict combined damage on the lock over its durability (which acts as its hit protection).

## Creating Locks

To create a lock, roll 1d12 per column below (3d12). 

| d12 | Lock Type (durability) | Sequence | Complication |
| --- | ---------------------- | -------- | ------------ |
| 1   | Crude (1)              | TPT      |              |
| 2   | Pin (2)                | TPR      |              |
| 3   | Bolt      (4)          | TRT      |              |
| 4   | Screw     (6)          | TRP      |              |
| 5   | Cylinder (8)           | PTP      | Cracked      |
| 6   | Anchor  (10)           | PTR      | Worn         |
| 7   | Warding (12)           | PRT      | Worn         |
| 8   | Elvish  (14)           | PRP      | Reinforced   |
| 9   | Goblin  (16)           | RTP      | Reinforced   |
| 10  | Dwarven (16)           | RTR      | Delicate     |
| 11  | Gnomish (16)           | RPT      | Delicate     |
| 12  | Strange (?)            | RPR      | Trapped      |

Once a lock type has a sequence assigned to it, that association is **permanent.** That is, if a gnomish lock results in the sequence RPR, that is always the sequence to unlock all future gnomish locks.

### Sequences

Once the lock is created, the referee should select or randomize the sequence required for picking the lock. Note that the sequence should be filled into the table above for every campaign that is run. All locks of the same type should unlock with the same sequence. 

### Lock Complications

| Complication | Effect                                                                 |
| ------------ | ---------------------------------------------------------------------- |
| Cracked      | Any action works on the first tumbler                                  |
| Worn         | First jam is ignored                                                   |
| Reinforced   | Double the durability                                                  |
| Delicate     | First mistake jams the lock                                            |
| Trapped      | Every mistake triggers a trap (needle, spray, etc) inflicting 1 damage |
