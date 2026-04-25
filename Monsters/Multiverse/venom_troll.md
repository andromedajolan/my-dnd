---
name: "Venom Troll"
size: "Large"
monster_type: "giant"
alignment: "Chaotic Evil"
cr: "7"
ac: "15 (natural armor)"
hp: "94 (9d10 + 45)"
speed: "walk 30 ft."
str: 18
dex: 13
con: 20
int: 7
wis: 9
cha: 7
saves: ""
skills: "+2"
immunities: "poison"
resistances: ""
vulnerabilities: ""
conditionImmunities: "poisoned"
senses: "darkvision 60 ft."
languages: "Giant"
image: ""
source: "MPMM"
---

# Venom Troll

*Large giant, Chaotic Evil*

### Traits
***Poison Splash.*** When the troll takes damage of any type but psychic, each creature within 5 feet of the troll takes 9 ({@damage 2d8}) poison damage.
***Regeneration.*** The troll regains 10 hit points at the start of each of its turns. If the troll takes acid or fire damage, this trait doesn't function at the start of the troll's next turn. The troll dies only if it starts its turn with 0 hit points and doesn't regenerate.

### Actions
***Multiattack.*** The troll makes one Bite attack and two Claw attacks.
***Bite.*** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}7 ({@damage 1d6 + 4}) piercing damage plus 4 ({@damage 1d8}) poison damage, and the creature is {@condition poisoned} until the start of the troll's next turn.
***Claws.*** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}11 ({@damage 2d6 + 4}) slashing damage plus 4 ({@damage 1d8}) poison damage.
***Venom Spray {@recharge}.*** The troll slices itself with a claw, releasing a spray of poison in a 15-foot cube. The troll takes 7 ({@damage 2d6}) slashing damage (this damage can't be reduced in any way). Each creature in the area must make a {@dc 16} Constitution saving throw. On a failed save, a creature takes 18 ({@damage 4d8}) poison damage and is {@condition poisoned} for 1 minute. On a successful save, the creature takes half as much damage and isn't {@condition poisoned}. A {@condition poisoned} creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

### Bonus Actions


### Reactions


### Legendary Actions

