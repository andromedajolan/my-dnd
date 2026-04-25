---
name: "Adult Red Dracolich"
size: "Medium"
monster_type: "dragon"
alignment: "Chaotic Evil"
cr: "17"
ac: "19 (natural armor)"
hp: "256 (19d12 + 133)"
speed: "walk 40 ft., climb 40 ft., fly 80 ft."
str: 27
dex: 10
con: 25
int: 16
wis: 13
cha: 21
saves: "+6, +13, +7, +11"
skills: "+13, +6"
immunities: "fire"
resistances: ""
vulnerabilities: ""
conditionImmunities: ""
senses: "blindsight 60 ft., darkvision 120 ft."
languages: "Common, Draconic"
image: ""
source: "TCE"
---
# Adult Red Dracolich

*Medium dragon, Chaotic Evil*

### Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.


### Actions

***Multiattack.*** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
***Bite.*** {@atk mw} {@hit 14} to hit, reach 10 ft., one target. {@h}19 ({@damage 2d10 + 8}) piercing damage plus 7 ({@damage 2d6}) fire damage.
***Claw.*** {@atk mw} {@hit 14} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d6 + 8}) slashing damage.
***Tail.*** {@atk mw} {@hit 14} to hit, reach 15 ft., one target. {@h}17 ({@damage 2d8 + 8}) bludgeoning damage.
***Frightful Presence.*** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a {@dc 19} Wisdom saving throw or become {@condition frightened} for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.
***Fire Breath {@recharge 5}.*** The dragon exhales fire in a 60-foot cone. Each creature in that area must make a {@dc 21} Dexterity saving throw, taking 63 ({@damage 18d6}) fire damage on a failed save, or half as much damage on a successful one.


### Bonus Actions




### Reactions




### Legendary Actions

***Detect.*** The dragon makes a Wisdom ({@skill Perception}) check.
***Tail Attack.*** The dragon makes a tail attack.
***Wing Attack (Costs 2 Actions).*** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a {@dc 22} Dexterity saving throw or take 15 ({@damage 2d6 + 8}) bludgeoning damage and be knocked {@condition prone}. The dragon can then fly up to half its flying speed.
