---
name: "Hierophant Medusa"
size: "Large"
monster_type: "monstrosity"
alignment: "Any Alignment"
cr: "17"
ac: "17 (natural armor)"
hp: "237 (25d10 + 100)"
speed: "walk 40 ft., climb 40 ft., swim 40 ft."
str: 22
dex: 20
con: 18
int: 15
wis: 23
cha: 22
saves: "+10, +12"
skills: "+12, +12, +12, +8, +11"
immunities: "poison"
resistances: ""
vulnerabilities: ""
conditionImmunities: "charmed, frightened, petrified, poisoned"
senses: ""
languages: "Common plus any three languages (Abyssal, Celestial, Druidic, or Infernal recommended)"
image: ""
source: "BMT"
---

# Hierophant Medusa

*Large monstrosity, Any Alignment*

### Traits
***Devotion's Call (1/Day).*** The medusa can cast the {@spell Resurrection} spell, requiring no material components and using Wisdom as the spellcasting ability.
***Legendary Resistance (4/Day).*** If the medusa fails a saving throw, it can choose to succeed instead.

### Actions
***Multiattack.*** The medusa makes one Constrict attack, one Final Blade attack, and one Snake Hair attack. Alternatively, it makes two Wrathful Strike attacks.
***Constrict.*** {@atk mw} {@hit 12} to hit, reach 10 ft., one target. {@h}16 ({@damage 3d6 + 6}) bludgeoning damage, and if the target is a Medium or smaller creature, it has the {@condition grappled} condition (escape {@dc 20}). Until this grapple ends, the target has the {@condition restrained} condition, and the medusa can't constrict another creature.
***Final Blade.*** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}13 ({@damage 2d6 + 6}) slashing damage plus 21 ({@damage 6d6}) force damage. If the target has at least one head and the medusa rolled a 20 on the attack roll, the target is decapitated and dies if it fails a {@dc 20} Constitution saving throw and can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 28 ({@damage 8d6}) force damage from the hit.
***Snake Hair.*** {@atk mw} {@hit 12} to hit, reach 5 ft., one target. {@h}11 ({@damage 1d10 + 6}) piercing damage plus 5 ({@damage 1d10}) poison damage.
***Wrathful Strike.*** {@atk rs} {@hit 12} to hit, range 120 ft., one creature. {@h}22 ({@damage 3d10 + 6}) radiant damage, and the target has the {@condition blinded} condition until the end of its next turn.

### Bonus Actions
***Petrifying Gaze {@recharge 4}.*** The medusa unleashes petrifying magic from its eyes in a 30-foot cone. Each creature in that area must make a {@dc 18} Constitution saving throw if it doesn't have the {@condition blinded} condition. If the saving throw fails by 5 or more, the creature has the {@condition petrified} condition. Otherwise, on a failed save, the creature takes 10 ({@damage 3d6}) force damage, begins to turn to stone, and has the {@condition restrained} condition. The {@condition restrained} creature must repeat the saving throw at the end of its next turn. On a failed save, it has the {@condition petrified} condition, and on a successful save, the effect ends on it. The petrification lasts until the creature is freed by the {@spell Greater Restoration} spell or other magic. A creature can use its reaction, if available, to shut its eyes to avoid the saving throw. If the creature does so, it has the {@condition blinded} condition until the end of its next turn.

### Reactions


### Legendary Actions
***Move.*** The medusa moves up to its speed without provoking opportunity attacks.
***Wrathful Blast (Costs 2 Actions).*** The medusa makes one Wrathful Strike attack.
***Final Slash (Costs 3 Actions).*** The medusa makes one Final Blade attack with advantage.
