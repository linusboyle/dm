---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/16
- monster/size/large
- monster/type/fiend
aliases: ["Shator Demodand"]
---
# Shator Demodand
*Source: Morte's Planar Parade p. 28*  

Shators, known as shaggy demodands, dominate demodand society, ruthlessly commanding their lesser kin. They are hulking creatures covered in fungal growths. Shators are the self-appointed wardens of Carceri, and they keep meticulous records of their subordinates and the prisoners they claim. On the rare occasions that shators find themselves on the Material Plane, they manipulate mortal leaders and philosophers, using them as mouthpieces to spread poisoned words and tempt souls toward Carceri's waiting chains.

## Demodands

Demodands, also called gehreleths, are Fiends from the Tarterian Depths of Carceri. Cast into the prison plane long ago for forgotten transgressions, these bitter, wicked creatures have appointed themselves the jailers of the plane. Demodands viciously defend the few known portals that lead out of Carceri and ruthlessly torment other creatures trapped there.

Demodands that manage to leave Carceri know they're doomed to return; a demodand that dies outside Carceri re-forms there in a torturous process that takes `2d20` days. Even those who survive on other planes find themselves eventually dragged back, pulled by some planar tether.

## Statblock

```ad-statblock
title: Shator Demodand
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MPP/Shator%20Demodand.webp#token)
*Large fiend, typically  Neutral Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 195 (`23d10 + 69`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|15 (+2)|17 (+3)|21 (+5)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +7, Wisdom +8
- **Skills** Perception +13, Stealth +7
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** cold, fire
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](5E2014官方资源/规则/conditions.md#charmed), [frightened](5E2014官方资源/规则/conditions.md#frightened), [paralyzed](5E2014官方资源/规则/conditions.md#paralyzed), [poisoned](5E2014官方资源/规则/conditions.md#poisoned), [restrained](5E2014官方资源/规则/conditions.md#restrained)
- **Languages** Abyssal, Common, Demodand, Infernal, telepathy 120 ft.
- **Challenge** 16

## Traits

***Boundless Movement.*** The shator ignores difficult terrain, and magical effects can't reduce its speed. It can spend 5 feet of movement to automatically remove the [grappled](5E2014官方资源/规则/conditions.md#grappled) condition from itself.

***Jailer (1/Day).*** The shator can cast the [imprisonment](5E2014官方资源/spells/imprisonment.md) spell, requiring no material components and using Intelligence as the spellcasting ability (chaining effect only; spell save DC 18).

***Liquefaction Ritual.*** The shator can perform a 1-minute ritual that turns all willing farastus and kelubars of its choice within 60 feet of itself into a living liquid form. Each liquefied demodand becomes enough liquid to fill a flask. A demodand's liquefaction lasts until a shator uses an action to end it or a creature opens a container holding the liquid. While liquefied in this way, a demodand has the [paralyzed](5E2014官方资源/规则/conditions.md#paralyzed) condition despite any immunity to that condition, it has immunity to all damage, and any curse affecting it is suspended.

***Magic Resistance.*** The shator has advantage on saving throws against spells and other magical effects.

***Numbing Secretions.*** A creature that touches the shator or hits it with a melee attack while within 5 feet of it must succeed on a DC 17 Dexterity saving throw or have disadvantage on attack rolls and its speed halved until the end of its next turn.

***Spellcasting.*** The shator casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 18, `+10` to hit with spell attacks):

**At will**: [invisibility](5E2014官方资源/spells/invisibility.md) (self only), [suggestion](5E2014官方资源/spells/suggestion.md)

**1/day each**: [dispel magic](5E2014官方资源/spells/dispel-magic.md), [plane shift](5E2014官方资源/spells/plane-shift.md) (to Carceri only), [scrying](5E2014官方资源/spells/scrying.md) (as an action)

## Actions

***Multiattack.*** The shator makes one Bite attack and two Enervating Trident attacks.

***Bite.*** *Melee Weapon Attack:* `+12` to hit, reach 5 ft., one target. *Hit:* 17 (`3d6 + 7`) piercing damage plus 26 (`4d12`) acid damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the [paralyzed](5E2014官方资源/规则/conditions.md#paralyzed) condition until the start of the shator's next turn.

***Enervating Trident.*** *Melee Weapon Attack:* `+12` to hit, reach 10 ft., one target. *Hit:* 18 (`2d10 + 7`) necrotic damage.

***Inhibitory Spray (Recharge 5-6).*** The shator exhales a spray of slime in a line 100 feet long and 5 feet wide. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 40 (`9d8`) acid damage and has the [paralyzed](5E2014官方资源/规则/conditions.md#paralyzed) condition for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.

***Summon Demodand (1/Day).*** The shator has a 50 percent chance of summoning its choice of `1d4` farastu demodands, `1d2` kelubar demodands, or 1 shator demodand. A summoned demodand appears in an unoccupied space within 60 feet of the shator, acts as an ally of the shator, and can't summon other demodands. It remains for 1 minute, until it or the shator dies, or until the shator dismisses it as an action.
```
^statblock