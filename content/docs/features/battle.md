---
title: Battle
type: docs
---


# Battle

Battle is the main game in Discord RPG bot game. The battle will be based on
player's stats and equipped armors, weapons, pet and skills. 

## Game

During battle, player and opponent will take turn to attack each round. This
battle is automated thus player does not have to do anything during battle. Once
any of the participants of the battle dies, the battle will stop and announces
the winner.

{{< figure
  src="https://res.cloudinary.com/hiremap/image/upload/v1640951581/screenshot-31-12-2021_19_51_14_boivhj.png" 
  width=450
>}}


## Attributes

{{< figure
  src="https://res.cloudinary.com/hiremap/image/upload/v1640951580/screenshot-31-12-2021_19_51_38_ozbl29.png" 
  width=450
>}}

### Attack
Attack is the attack rate when player hits the opponent.

### Armor
Armor is the amount of attack rate blocked in percentage when defending. For
example, `12.2%` armor blocks `12.2%` attack of the opponent.

### HP
HP is the health point of the player during the battle. Both player and opponent
attacks each other until one of their HP reaches 0.

{{< hint info >}}
HP replenishes once battle ends. There is no need to heal the player.
{{< /hint >}}

### Critical Attack
Critical attack is the multiplier when a user does a critical attack.

### Critical Chance
Critical chance is the percentage of likeliness to hit a critical attack in a
round.

