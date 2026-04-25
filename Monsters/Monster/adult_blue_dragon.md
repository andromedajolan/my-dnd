---
name: "Adult Blue Dragon"
size: "Huge"
monster_type: "dragon"
alignment: "Lawful Evil"
cr: "16"
ac: "19 (natural armor)"
hp: "225 (18d12 + 108)"
speed: "walk 40 ft., burrow 30 ft., fly 80 ft."
str: 25
dex: 10
con: 23
int: 16
wis: 15
cha: 19
saves: "+5, +11, +7, +9"
skills: "+12, +5"
immunities: "lightning"
resistances: ""
vulnerabilities: ""
conditionImmunities: ""
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "MM"
---

# Adult Blue Dragon

*Huge dragon, Lawful Evil*

### Traits
***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}18 ({@damage 2d10 + 7}) piercing damage plus 5 ({@damage 1d10}) lightning damage.
***Claw.*** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}14 ({@damage 2d6 + 7}) slashing damage.
***Tail.*** {@atk mw} {@hit 12} to hit, reach 15 ft., one target. {@h}16 ({@damage 2d8 + 7}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 17} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Lightning Breath {@recharge 5}.*** The dragon exhales lightning in a 90-foot line that is 5 feet wide. Each creature in that line must make a {@dc 19} Dexterity saving throw, taking 66 ({@damage 12d10}) lightning damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a {@dc 20} Dexterity saving throw or take 14 ({@damage 2d6 + 7}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
