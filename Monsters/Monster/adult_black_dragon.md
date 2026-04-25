---
name: "Adult Black Dragon"
size: "Huge"
monster_type: "dragon"
alignment: "Chaotic Evil"
cr: "14"
ac: "19 (natural armor)"
hp: "195 (17d12 + 85)"
speed: "walk 40 ft., fly 80 ft., swim 40 ft."
str: 23
dex: 14
con: 21
int: 14
wis: 13
cha: 17
saves: "+7, +10, +6, +8"
skills: "+11, +7"
immunities: "acid"
resistances: ""
vulnerabilities: ""
conditionImmunities: ""
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "MM"
---

# Adult Black Dragon

*Huge dragon, Chaotic Evil*

### Traits
***Amphibious.*** The dragon can breathe air and water.
***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 11} to hit, reach 10 ft., one target. {@h}17 ({@damage 2d10 + 6}) piercing damage plus 4 ({@damage 1d8}) acid damage.
***Claw.*** {@atk mw} {@hit 11} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage.
***Tail.*** {@atk mw} {@hit 11} to hit, reach 15 ft., one target. {@h}15 ({@damage 2d8 + 6}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 16} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Acid Breath {@recharge 5}.*** The dragon exhales acid in a 60-foot line that is 5 feet wide. Each creature in that line must make a {@dc 18} Dexterity saving throw, taking 54 ({@damage 12d8}) acid damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a {@dc 19} Dexterity saving throw or take 13 ({@damage 2d6 + 6}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
