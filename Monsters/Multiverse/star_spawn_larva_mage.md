---
name: "Star Spawn Larva Mage"
size: "Medium"
monster_type: "aberration"
alignment: "Chaotic Evil"
cr: "16"
ac: "16 (natural armor)"
hp: "168 (16d8 + 96)"
speed: "walk 30 ft."
str: 17
dex: 12
con: 23
int: 18
wis: 12
cha: 16
saves: "+6, +6, +8"
skills: "+6"
immunities: "psychic"
resistances: "cold, bludgeoning, piercing, slashing (from nonmagical attacks)"
vulnerabilities: ""
conditionImmunities: "charmed, frightened, paralyzed, petrified, poisoned, restrained"
senses: "darkvision 60 ft."
languages: "Deep Speech"
image: ""
source: "MPMM"
---

# Star Spawn Larva Mage

*Medium aberration, Chaotic Evil*

### Traits
***Return to Worms.*** When the mage is reduced to 0 hit points, it breaks apart into a {@creature swarm of insects} in the same space. Unless the swarm is destroyed, the mage reforms from it 24 hours later.

### Actions
***Multiattack.*** The mage makes three Slam or Eldritch Bolt attacks.
***Slam.*** {@atk mw} {@hit 8} to hit, reach 10 ft., one target. {@h}7 ({@damage 1d8 + 3}) bludgeoning damage, and the target must succeed on a {@dc 19} Constitution saving throw or be {@condition poisoned} until the end of its next turn.
***Eldritch Bolt.*** {@atk rs} {@hit 8} to hit, range 60 ft., one target. {@h}19 ({@damage 3d10 + 3}) force damage.
***Plague of Worms {@recharge}.*** Each creature other than a star spawn within 10 feet of the mage must succeed on a {@dc 19} Dexterity saving throw or take 22 ({@damage 5d8}) necrotic damage and be {@condition blinded} and {@condition restrained} by masses of swarming worms. The affected creature takes 22 ({@damage 5d8}) necrotic damage at the start of each of the mage's turns. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

### Bonus Actions


### Reactions
***Feed on Weakness.*** When a creature within 20 feet of the mage fails a saving throw, the mage gains 10 temporary hit points.

### Legendary Actions
***Slam.*** The mage makes one Slam attack.
***Eldritch Bolt (Costs 2 Actions).*** The mage makes one Eldritch Bolt attack.
***Feed (Costs 3 Actions).*** Each creature {@condition restrained} by the mage's Plague of Worms takes 13 ({@damage 3d8}) necrotic damage, and the mage gains 6 temporary hit points.
