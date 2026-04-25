---
name: "Zaratan"
size: "Gargantuan"
monster_type: "elemental"
alignment: "Neutral"
cr: "22"
ac: "21 (natural armor)"
hp: "307 (15d20 + 150)"
speed: "walk 40 ft., swim 40 ft."
str: 30
dex: 10
con: 30
int: 2
wis: 21
cha: 18
saves: "+12, +11"
skills: ""
immunities: "poison"
resistances: "cold, fire, lightning, bludgeoning, piercing, slashing (from nonmagical attacks)"
vulnerabilities: ""
conditionImmunities: "exhaustion, paralyzed, petrified, poisoned, stunned"
senses: "darkvision 60 ft., tremorsense 60 ft."
languages: ""
image: ""
source: "MPMM"
---

# Zaratan

*Gargantuan elemental, Neutral*

### Traits
***Legendary Resistance (3/Day).*** If the zaratan fails a saving throw, it can choose to succeed instead.
***Siege Monster.*** The elemental deals double damage to objects and structures (included in Earth-Shaking Movement).

### Actions
***Multiattack.*** The zaratan makes one Bite attack and one Stomp attack.
***Bite.*** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}28 ({@damage 4d8 + 10}) force damage.
***Stomp.*** {@atk mw} {@hit 17} to hit, reach 20 ft., one target. {@h}26 ({@damage 3d10 + 10}) thunder damage.
***Spit Rock.*** {@atk rw} {@hit 17} to hit, range 120 ft./240 ft., one target. {@h}31 ({@damage 6d8 + 10}) force damage.
***Spew Debris {@recharge 5}.*** The zaratan exhales rocky debris in a 90-foot cube. Each creature in that area must make a {@dc 25} Dexterity saving throw. A creature takes 33 ({@damage 6d10}) bludgeoning damage on a failed save, or half as much damage on a successful one. A creature that fails the save by 5 or more is knocked {@condition prone}.

### Bonus Actions
***Earth-Shaking Movement.*** After moving at least 10 feet on the ground, the zaratan sends a shock wave through the ground in a 120-foot-radius circle centered on itself. That area becomes {@quickref difficult terrain||3} for 1 minute. Each creature on the ground that is {@status concentration||concentrating} must succeed on a {@dc 25} Constitution saving throw or the creature's {@status concentration} is broken. The shock wave deals 100 thunder damage to all structures in contact with the ground in the area. If a creature is near a structure that collapses, the creature might be buried; a creature within half the distance of the structure's height must make a {@dc 25} Dexterity saving throw. On a failed save, the creature takes 17 ({@damage 5d6}) bludgeoning damage, is knocked {@condition prone}, and is trapped in the rubble. A trapped creature is {@condition restrained}, requiring a successful {@dc 20} Strength ({@skill Athletics}) check as an action to escape. Another creature within 5 feet of the buried creature can use its action to clear rubble and grant advantage on the check. If three creatures use their actions in this way, the check is an automatic success. On a successful save, the creature takes half as much damage and doesn't fall {@condition prone} or become trapped.

### Reactions


### Legendary Actions
***Stomp.*** The zaratan makes one Stomp attack.
***Move.*** The zaratan moves up to its speed.
***Spit (Costs 2 Actions).*** The zaratan makes one Spit Rock attack.
***Retract (Costs 2 Actions).*** The zaratan retracts into its shell. Until it takes its Emerge action, it has resistance to all damage, and it is {@condition restrained}. The next time it takes a legendary action, it must take its Revitalize or Emerge action.
***Revitalize (Costs 2 Actions).*** The zaratan can use this option only if it is retracted in its shell. It regains 52 ({@dice 5d20}) hit points. The next time it takes a legendary action, it must take its Emerge action.
***Emerge (Costs 2 Actions).*** The zaratan emerges from its shell and makes one Spit Rock attack. It can use this option only if it is retracted in its shell.
