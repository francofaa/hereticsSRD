---
title: Lockpicking
layout: default
permalink: /lockpicking
nav_order: 4
parent: Procedures
---

{% include toc.html %}

# Lockpicking

To pick a lock, the character tries an action to unlock a tumbler. Every lock has three tumblers. The actions are:

- Tap
- Probe
- Rake

## Qualities of Locks

1. Each lock has three tumblers, each of which which require an action. Additionally, no two sequential tumblers require the same action. 
2. Each lock type requires the same set of actions once it is solved. When a lock is solved, every other lock of that type is solved in the same manner. In this manner, the character gains expertise in lockpicking. 
3. Each lock has a durability score that acts like hit protection. At zero, the lock is broken off.

## Picking Procedure

A character chooses one of the three actions (tap, probe, rake) to unlock the tumblers of the lock. On a failure, the lock becomes stiff. On a subsequent success the lock is no longer stiff. 

A failure on a stiff lock results in the lock getting jammed. It must be broken off. To break a lock off, the character must inflict combined damage on the lock over its durability (which acts as its hit protection).

## Creating Locks

Randomize or choose a lock type. Each has a durability score.

| d6  | Lock Type | Durability | Sequence |
| --- | --------- | ---------- | -------- |
| 1   | Pin       | 4          |          |
| 2   | Bolt      | 6          |          |
| 3   | Screw     | 8          |          |
| 4   | Cylinder  | 10         |          |
| 5   | Warding   | 12         |          |
| 6   | Strange   | ?          |          |

### Sequences

Once the lock is created, the referee should select or randomize the sequence required for picking the lock. Note that the sequence should be filled into the table above for every campaign that is run. All locks of the same type should unlock with the same sequence. 

The sequences follow below, where T = Tap, P = Probe, and R = Rake

1. TPT
2.  TPR
3.  TRT
4.  TRP
5.  PTP
6.  PTR
7.  PRT
8.  PRP
9.  RTP
10.  RTR
11.  RPT
12.  RPR

### Sub-Categories of Locks

Since there are a total of 12 possible combinations and 6 lock types, additional variations can be added to lock types, like an Elvish bolt lock or a Dwarven-forged screw lock. 

### Lock Complications

Complications may be added to the locks. These complications can be rolled on a d6 table: 

| d6  | Complication | Effect                                                                 |
| --- | ------------ | ---------------------------------------------------------------------- |
| 1   | Cracked      | Any action works on the first tumbler                                  |
| 2   | Worn         | First jam is ignored                                                   |
| 3   | Normal       |                                                                        |
| 4   | Reinforced   | Double the durability                                                  |
| 5   | Delicate     | First mistake jams the lock                                            |
| 6   | Trapped      | Every mistake triggers a trap (needle, spray, etc) inflicting 1 damage |
