---
name: "Ancient Blue Dragon"
size: "Gargantuan"
monster_type: "dragon"
alignment: "Lawful Evil"
cr: "23"
ac: "22 (natural armor)"
hp: "481 (26d20 + 208)"
speed: "walk 40 ft., burrow 40 ft., fly 80 ft."
str: 29
dex: 10
con: 27
int: 18
wis: 17
cha: 21
saves: "+7, +15, +10, +12"
skills: "+17, +7"
immunities: "lightning"
resistances: ""
vulnerabilities: ""
conditionImmunities: ""
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "MM"
---

# Ancient Blue Dragon

*Gargantuan dragon, Lawful Evil*

### Traits
***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 16} to hit, reach 15 ft., one target. {@h}20 ({@damage 2d10 + 9}) piercing damage plus 11 ({@damage 2d10}) lightning damage.
***Claw.*** {@atk mw} {@hit 16} to hit, reach 10 ft., one target. {@h}16 ({@damage 2d6 + 9}) slashing damage.
***Tail.*** {@atk mw} {@hit 16} to hit, reach 20 ft., one target. {@h}18 ({@damage 2d8 + 9}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 20} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Lightning Breath {@recharge 5}.*** The dragon exhales lightning in a 120-foot line that is 10 feet wide. Each creature in that line must make a {@dc 23} Dexterity saving throw, taking 88 ({@damage 16d10}) lightning damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a {@dc 24} Dexterity saving throw or take 16 ({@damage 2d6 + 9}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
