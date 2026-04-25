---
name: "Adult Green Dragon"
size: "Huge"
monster_type: "dragon"
alignment: "Lawful Evil"
cr: "15"
ac: "19 (natural armor)"
hp: "207 (18d12 + 90)"
speed: "walk 40 ft., fly 80 ft., swim 40 ft."
str: 23
dex: 12
con: 21
int: 18
wis: 15
cha: 17
saves: "+6, +10, +7, +8"
skills: "+8, +7, +12, +8, +6"
immunities: "poison"
resistances: ""
vulnerabilities: ""
conditionImmunities: "poisoned"
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "MM"
---

# Adult Green Dragon

*Huge dragon, Lawful Evil*

### Traits
***Amphibious.*** The dragon can breathe air and water.
***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 7 ({@damage 2d6}) poison damage.
***Claw.*** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage.
***Tail.*** {@atk mw} {@hit 11} to hit, reach 15 ft., one target. {@h}15 ({@damage 2d8 + 6}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 16} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Poison Breath {@recharge 5}.*** The dragon exhales poisonous gas in a 60-foot cone. Each creature in that area must make a {@dc 18} Constitution saving throw, taking 56 ({@damage 16d6}) poison damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a {@dc 19} Dexterity saving throw or take 13 ({@damage 2d6 + 6}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
