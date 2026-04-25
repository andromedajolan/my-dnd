---
name: "Mage Hunter"
size: "Large"
monster_type: "monstrosity"
alignment: "Lawful Evil"
cr: "5"
ac: "15 (natural armor)"
hp: "85 (10d10 + 30)"
speed: "walk 40 ft., climb 40 ft. (hunter form only), fly 10 ft. (hover sentry form only)"
str: 19
dex: 15
con: 16
int: 11
wis: 17
cha: 10
saves: "+3, +6, +3"
skills: "+9, +5"
immunities: ""
resistances: ""
vulnerabilities: ""
conditionImmunities: "blinded, charmed, deafened, frightened, prone"
senses: "blindsight 120 ft. (blind beyond this radius)"
languages: "understands Common but can't speak"
image: ""
source: "SCC"
---

# Mage Hunter

*Large monstrosity, Lawful Evil*

### Traits
***Magic Sense.*** The hunter knows the location of every spellcaster, active spell, and magic item within 120 feet of itself.
***Spider Climb (Hunter Form Only).*** The hunter can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

### Actions
***Multiattack (Hunter Form Only).*** The hunter makes two Claw attacks.
***Claw (Hunter Form Only).*** {@atk mw} {@hit 7} to hit, reach 5 ft., one target. {@h}15 ({@damage 2d10 + 4}) slashing damage.
***Tail.*** {@atk mw} {@hit 7} to hit, reach 10 ft., one target. {@h}22 ({@damage 4d8 + 4}) piercing damage, and the target is {@condition grappled} (escape {@dc 15}). Until this grapple ends, the target is {@condition restrained}, and the hunter can't make a Tail attack against another target.
***Mage Tracker (Sentry Form Only).*** The hunter emits a pulse of energy that helps it better locate its magical quarry. Each creature within 120 feet of the hunter that has the ability to cast spells must succeed on a {@dc 14} Wisdom saving throw or be mystically marked by the hunter for 1 hour. While marked, a creature can't become hidden from the hunter and gains no benefit from the {@condition invisible} condition against the hunter. Additionally, while a marked creature is on the same plane of existence as the hunter, the hunter always knows the distance and direction to the creature.

### Bonus Actions
***Shift Form.*** The hunter folds into its drone-like sentry form or unfolds into its hunter form. Its game statistics are the same in each form.

### Reactions
***Consume and Destroy.*** When the hunter takes damage from a spell, it takes only half the triggering damage (rounded down). If the creature that cast the spell is within 60 feet of the hunter, that creature must succeed on a {@dc 14} Dexterity saving throw or take the other half of the damage.

### Legendary Actions

