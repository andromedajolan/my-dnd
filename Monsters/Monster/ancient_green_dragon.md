---
name: "Ancient Green Dragon"
size: "Gargantuan"
monster_type: "dragon"
alignment: "Lawful Evil"
cr: "22"
ac: "21 (natural armor)"
hp: "385 (22d20 + 154)"
speed: "walk 40 ft., fly 80 ft., swim 40 ft."
str: 27
dex: 12
con: 25
int: 20
wis: 17
cha: 19
saves: "+8, +14, +10, +11"
skills: "+11, +10, +17, +11, +8"
immunities: "poison"
resistances: ""
vulnerabilities: ""
conditionImmunities: "poisoned"
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "MM"
---

# Ancient Green Dragon

*Gargantuan dragon, Lawful Evil*

### Traits
***Amphibious.*** The dragon can breathe air and water.
***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 15} to hit, reach 15 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 10 ({@damage 3d6}) poison damage.
***Claw.*** {@atk mw} {@hit 15} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d6 + 8}) slashing damage.
***Tail.*** {@atk mw} {@hit 15} to hit, reach 20 ft., one target. {@h}17 ({@damage 2d8 + 8}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 19} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Poison Breath {@recharge 5}.*** The dragon exhales poisonous gas in a 90-foot cone. Each creature in that area must make a {@dc 22} Constitution saving throw, taking 77 ({@damage 22d6}) poison damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a {@dc 23} Dexterity saving throw or take 15 ({@damage 2d6 + 8}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
