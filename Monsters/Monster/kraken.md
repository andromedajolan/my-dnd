---
name: "Kraken"
size: "Gargantuan"
monster_type: "monstrosity (titan)"
alignment: "Chaotic Evil"
cr: "23"
ac: "18 (natural armor)"
hp: "472 (27d20 + 189)"
speed: "walk 20 ft., swim 60 ft."
str: 30
dex: 11
con: 25
int: 22
wis: 18
cha: 20
saves: "+17, +7, +14, +13, +11"
skills: ""
immunities: "lightning, bludgeoning, piercing, slashing (from nonmagical attacks)"
resistances: ""
vulnerabilities: ""
conditionImmunities: "frightened, paralyzed"
senses: "truesight 120 ft."
languages: "Abyssal, Celestial, Infernal, Primordial, telepathy 120 ft. but can't speak"
image: ""
source: "MM"
---

# Kraken

*Gargantuan monstrosity (titan), Chaotic Evil*

### Traits
***Amphibious.*** The kraken can breathe air and water.
***Freedom of Movement.*** The kraken ignores {@quickref difficult terrain||3}, and magical effects can't reduce its speed or cause it to be {@condition restrained}. It can spend 5 feet of movement to escape from nonmagical restraints or being {@condition grappled}.
***Siege Monster.*** The kraken deals double damage to objects and structures.

### Actions
***Multiattack.*** The kraken makes three tentacle attacks, each of which it can replace with one use of Fling.
***Bite.*** {@atk mw} {@hit 17} to hit, reach 5 ft., one target. {@h}23 ({@damage 3d8 + 10}) piercing damage. If the target is a Large or smaller creature {@condition grappled} by the kraken, that creature is swallowed, and the grapple ends. While swallowed, the creature is {@condition blinded} and {@condition restrained}, it has {@quickref Cover||3||total cover} against attacks and other effects outside the kraken, and it takes 42 ({@damage 12d6}) acid damage at the start of each of the kraken's turns. If the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a {@dc 25} Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall {@condition prone} in a space within 10 feet of the kraken. If the kraken dies, a swallowed creature is no longer {@condition restrained} by it and can escape from the corpse using 15 feet of movement, exiting {@condition prone}.
***Tentacle.*** {@atk mw} {@hit 17} to hit, reach 30 ft., one target. {@h}20 ({@damage 3d6 + 10}) bludgeoning damage, and the target is {@condition grappled} (escape {@dc 18}). Until this grapple ends, the target is {@condition restrained}. The kraken has ten tentacles, each of which can grapple one target.
***Fling.*** One Large or smaller object held or creature {@condition grappled} by the kraken is thrown up to 60 feet in a random direction and knocked {@condition prone}. If a thrown target strikes a solid surface, the target takes 3 ({@damage 1d6}) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a {@dc 18} Dexterity saving throw or take the same damage and be knocked {@condition prone}.
***Lightning Storm.*** The kraken magically creates three bolts of lightning, each of which can strike a target the kraken can see within 120 feet of it. A target must make a {@dc 23} Dexterity saving throw, taking 22 ({@damage 4d10}) lightning damage on a failed save, or half as much damage on a successful one.

### Bonus Actions


### Reactions


### Legendary Actions
***Tentacle Attack or Fling.*** The kraken makes one tentacle attack or uses its Fling.
***Lightning Storm (Costs 2 Actions).*** The kraken uses Lightning Storm.
***Ink Cloud (Costs 3 Actions).*** While underwater, the kraken expels an ink cloud in a 60-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than the kraken. Each creature other than the kraken that ends its turn there must succeed on a {@dc 23} Constitution saving throw, taking 16 ({@damage 3d10}) poison damage on a failed save, or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of the kraken's next turn.
