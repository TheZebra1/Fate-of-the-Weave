An enigmatic shadow druid, who wishes nothing but to become one with the Shadow's and to help all Druid's realize that when sentients occupy an area they brighten it with their bright lights and decimate the land however they see fit, but they cower before darkness. In the dark, those who most commonly destroy nature are lost while nature is able to thrive and expand.
![[Brigham Alikir.jpg|500]]
![[Shadow Sapling.jpg|500]]

```statblock
name: Druid of the Circle of Shadows
size: Medium
type: Humanoid
subtype: Shapechanger
alignment: Neutral Evil
ac: 16
hp: 130
hit_dice: 15d8 + 45
speed: 30 ft.
stats:
  - 10
  - 16
  - 14
  - 12
  - 18
  - 20
saves:
  - Wisdom: 10
  - Dexterity: 7
  - Constitution: 6
skillsaves:
  - Stealth: 12
  - Nature: 5
  - Perception: 10
damage_resistances: necrotic, bludgeoning/piercing/slashing (while in dim light or darkness)
damage_immunities: ""
condition_immunities: ""
senses: Darkvision 90 ft. (60 ft. + 30 ft. from Strength of the Shadows), passive Perception 20
languages: Common, Druidic, Sylvan
cr: "8"
bestiary: true
traits:
  - name: Bonus Cantrip
    desc: The druid can cast Minor Illusion or Chill Touch as bonus cantrips.
  - name: Strength of the Shadows
    desc: The druid has resistance to necrotic damage and has Darkvision up to 60 ft. If they already have Darkvision, it is extended by 30 ft.
  - name: Call of the Shadowseeds
    desc: Whenever the druid deals necrotic damage, they can summon a Blighted Sapling. The sapling can immediately attack using the druid's spell attack modifier and deals 2d4 + Proficiency Bonus piercing damage. It gains multiattack at higher levels.
  - name: Boogieman
    desc: The druid can hide as a bonus action. Gains proficiency in Stealth, and in dim light or darkness, adds Wisdom modifier to Stealth checks. While in darkness or dim light, the druid also gains resistance to bludgeoning, piercing, and slashing damage.
  - name: Fear the Dark
    desc: When the druid hits a target with a spell attack while either they or the target are in dim light or darkness, the spell deals extra necrotic damage equal to the druid’s Wisdom modifier (+5). The druid can also force the target to make a Wisdom saving throw (DC 18), becoming frightened on a failed save until the end of the target's next turn.
  - name: Shadowshift
    desc: The druid can expend a use of their Wild Shape to assume the form of a Shadow.
  - name: Life Drain (Shadow Form)
    desc: While in Shadow Form, the druid heals for half the damage dealt.
  - name: Sunlight Sensitivity (Shadow Form)
    desc: While in Shadow Form, the druid suffers from Sunlight Sensitivity and vulnerability to radiant damage.
actions:
  - name: Multiattack
    desc: The druid can make two melee attacks, or cast a spell and make one melee attack.
    attack_bonus: 0
  - name: Life Drain (Shadow Form)
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (2d6 + 2) necrotic damage, and the druid heals for half the damage dealt."
    attack_bonus: 8
    damage_dice: 2d6
    damage_bonus: 2
spells:
  - "The druid is a 15th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 18, +10 to hit with spell attacks). The druid has the following spells prepared:"
  - Cantrips (at will): Chill Touch, Minor Illusion, Druidcraft, Shillelagh
  - 1st level (4 slots): Entangle, Faerie Fire, Cure Wounds, Detect Magic
  - 2nd level (3 slots): Moonbeam, Pass without Trace, Hold Person
  - 3rd level (3 slots): Call Lightning, Dispel Magic, Conjure Animals
  - 4th level (3 slots): Shadow Blade, Darkness, Grasping Vine, Polymorph
  - 5th level (2 slots): Bestow Curse, Mass Cure Wounds, Insect Plague
  - 6th level (1 slot): Shadow of Moil, Heal
  - 7th level (1 slot): Evard's Black Tentacles, Regenerate
  - 8th level (1 slot): Negative Energy Flood, Feeblemind
legendary_description: The druid can use Legendary Resistance (2/day). If they fail a saving throw, they can choose to succeed instead.
reactions:
  - name: Counterspell
    desc: When another creature within 60 feet casts a spell, the druid can use their reaction to attempt to interrupt the spell. If the spell is 3rd level or lower, it automatically fails. If it is 4th level or higher, the druid must make an ability check using their spellcasting ability. The DC equals 10 + the spell's level.

```