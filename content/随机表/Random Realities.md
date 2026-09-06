---
title: Random Realities
date: 2026-09-04
aliases: []
tags: []
---

This file uses the [Dice Roller](https://plugins.javalent.com/Dice+Roller/Dice+Roller) plugin to roll random results from the tables. Below are several examples of how to use it:

Link an entire section in your document:
![[Random Realities#World]]

There are also block IDs for each section so you can include it without the header, for example:
> [!question]+ What is this world like?
> ![[Random Realities#^world]]

And each individual attribute has it's own formula table, so you can roll them like this:
What happens as we travel? `dice: [[Random Realities#^exploration-event]]`

# Categories
## Fate
• d66: `dice: [[Random Realities#^fate-d66]]` • d4: `dice: [[Random Realities#^fate-d4]]` • d12: `dice: [[Random Realities#^fate-d12]]`  Chance: `dice: [[Random Realities#^fate-chance]]`
^fate

## General

- Simple: `dice: [[Random Realities#^general-simple]]`
- Complex: `dice: [[Random Realities#^general-complex]]`
- Abstract: `dice: [[Random Realities#^general-abstract]]`
- Intensity: `dice: [[Random Realities#^general-intensity]]`

^general

## World

- Name: `dice: [[Random Realities#^world-name]]`
- Aspects: `dice: [[Random Realities#^world-aspects]]`
- Inhabitants: `dice: [[Random Realities#^world-inhabitants]]`
- Icon: `dice: [[Random Realities#^world-icon]]`

^world

## Exploration
- Terrain: `dice: [[Random Realities#^exploration-terrain]]`
- Ornament: `dice: [[Random Realities#^exploration-ornament]]`
- Event: `dice: [[Random Realities#^exploration-event]]`
- Findings: `dice: [[Random Realities#^exploration-findings]]`
- Icons: `dice: [[Random Realities#^exploration-icon]]`

^exploration
## Creation
- Purpose: `dice: [[Random Realities#^creation-purpose]]`
- Trait: `dice: [[Random Realities#^creation-trait]]`
- Magic: `dice: [[Random Realities#^creation-magic]]`
- Corruption: `dice: [[Random Realities#^creation-corruption]]`
- Icon: `dice: [[Random Realities#^creation-icon]]`

^creation

## Scene
- Challenge: `dice: [[Random Realities#^scene-challenge]]`
- Reaction: `dice: [[Random Realities#^scene-reaction]]`
- Senses: `dice: [[Random Realities#^scene-senses]]`
- Activity: `dice: [[Random Realities#^scene-activity]]`
- Detail: `dice: [[Random Realities#^scene-detail]]`
- Development: `dice: [[Random Realities#^scene-development]]`
- Complication: `dice: [[Random Realities#^scene-complication]]`
- Advantage: `dice: [[Random Realities#^scene-advantage]]`

^scene

## Quest
- Mission: `dice: [[Random Realities#^quest-mission]]`
- Opposition: `dice: [[Random Realities#^quest-opposition]]`
- Hindrance: `dice: [[Random Realities#^quest-hindrance]]`
- Aid: `dice: [[Random Realities#^quest-aid]]`
- Escalation: `dice: [[Random Realities#^quest-escalation]]`
- Reward: `dice: [[Random Realities#^quest-reward]]`
- Twist: `dice: [[Random Realities#^quest-twist]]`
- Progress: `dice: [[Random Realities#^quest-progress]]`
- Tension: `dice: [[Random Realities#^quest-tension]]`

^quest

## Location
- Past: `dice: [[Random Realities#^location-past]]`
- Present: `dice: [[Random Realities#^location-present]]`
- Descriptor: `dice: [[Random Realities#^location-descriptor]]`
- Trouble: `dice: [[Random Realities#^location-trouble]]`
- Building: `dice: [[Random Realities#^location-building]]`
- Influence: `dice: [[Random Realities#^location-influence]]`
- Mood: `dice: [[Random Realities#^location-mood]]`
- Rumor: `dice: [[Random Realities#^location-rumor]]`
- Seeks: `dice: [[Random Realities#^location-seeks]]`
- Offers: `dice: [[Random Realities#^location-offers]]`

^location

## People
- Name: `dice: [[Random Realities#^people-name]]`
- Disposition: `dice: [[Random Realities#^people-disposition]]`
- Role: `dice: [[Random Realities#^people-role]]`
- Descriptor: `dice: [[Random Realities#^people-descriptor]]`
- Quirk: `dice: [[Random Realities#^people-quirk]]`
- Drive: `dice: [[Random Realities#^people-drive]]`
- Secret: `dice: [[Random Realities#^people-secret]]`
- Seeks: `dice: [[Random Realities#^people-seeks]]`
- Offers: `dice: [[Random Realities#^people-offers]]`

^people

## Creature
- Name: `dice: [[Random Realities#^creature-name]]`
- Form: `dice: [[Random Realities#^creature-form]]`
- Power: `dice: [[Random Realities#^creature-power]]`
- Feature: `dice: [[Random Realities#^creature-feature]]`
- Action: `dice: [[Random Realities#^creature-action]]`

^creature

# Formula Tables

| dice: 1d1 | fate-d66                                     |
| --------- | -------------------------------------------- |
| 1         | `dice: [[Random Realities#^data]]\|fate-d66` |
^fate-d66

| dice: 1d1 | fate-d4 |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|fate-d4` |
^fate-d4

| dice: 1d1 | fate-d12 |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|fate-d12` |
^fate-d12

| dice: 1d1 | fate-chance |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|fate-chance` |
^fate-chance

| dice: 1d1 | general-simple |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|general-simple` |
^general-simple

| dice: 1d1 | general-complex |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|general-complex-1`—`dice: [[Random Realities#^data]]\|general-complex-2`—`dice: [[Random Realities#^data]]\|general-complex-3` |
^general-complex

| dice: 1d1 | general-abstract |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|general-abstract-1`—`dice: [[Random Realities#^data]]\|general-abstract-2` |
^general-abstract

| dice: 1d1 | general-intensity |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|general-intensity` |
^general-intensity

| dice: 1d1 | world-name |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|world-name-1`—`dice: [[Random Realities#^data]]\|world-name-2` |
^world-name

| dice: 1d1 | world-aspects |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|world-aspects-1`—`dice: [[Random Realities#^data]]\|world-aspects-2` |
^world-aspects

| dice: 1d1 | world-inhabitants |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|world-inhabitants-1`—`dice: [[Random Realities#^data]]\|world-inhabitants-2` |
^world-inhabitants

| dice: 1d1 | world-icon |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|world-icon-1`—`dice: [[Random Realities#^data]]\|world-icon-2`—`dice: [[Random Realities#^data]]\|world-icon-3`—`dice: [[Random Realities#^data]]\|world-icon-4` |
^world-icon

| dice: 1d1 | exploration-terrain |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|exploration-terrain-1`—`dice: [[Random Realities#^data]]\|exploration-terrain-2` |
^exploration-terrain

| dice: 1d1 | exploration-ornament |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|exploration-ornament-1`—`dice: [[Random Realities#^data]]\|exploration-ornament-2` |
^exploration-ornament

| dice: 1d1 | exploration-event |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|exploration-event-1`—`dice: [[Random Realities#^data]]\|exploration-event-2` |
^exploration-event

| dice: 1d1 | exploration-findings |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|exploration-findings-1`—`dice: [[Random Realities#^data]]\|exploration-findings-2` |
^exploration-findings

| dice: 1d1 | exploration-icon |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|exploration-icon-1`—`dice: [[Random Realities#^data]]\|exploration-icon-2`—`dice: [[Random Realities#^data]]\|exploration-icon-3`—`dice: [[Random Realities#^data]]\|exploration-icon-4` |
^exploration-icon

| dice: 1d1 | creation-purpose |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creation-purpose` |
^creation-purpose

| dice: 1d1 | creation-trait |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creation-trait` |
^creation-trait

| dice: 1d1 | creation-magic |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creation-magic-1`—`dice: [[Random Realities#^data]]\|creation-magic-2` |
^creation-magic

| dice: 1d1 | creation-corruption |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creation-corruption` |
^creation-corruption

| dice: 1d1 | creation-icon |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creation-icon-1`—`dice: [[Random Realities#^data]]\|creation-icon-2`—`dice: [[Random Realities#^data]]\|creation-icon-3`—`dice: [[Random Realities#^data]]\|creation-icon-4` |
^creation-icon

| dice: 1d1 | scene-challenge |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-challenge-1`—`dice: [[Random Realities#^data]]\|scene-challenge-2` |
^scene-challenge

| dice: 1d1 | scene-reaction |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-reaction-1`—`dice: [[Random Realities#^data]]\|scene-reaction-2` |
^scene-reaction

| dice: 1d1 | scene-senses |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-senses-1`—`dice: [[Random Realities#^data]]\|scene-senses-2` |
^scene-senses

| dice: 1d1 | scene-activity |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-activity` |
^scene-activity

| dice: 1d1 | scene-detail |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-detail` |
^scene-detail

| dice: 1d1 | scene-development |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-development` |
^scene-development

| dice: 1d1 | scene-complication |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-complication` |
^scene-complication

| dice: 1d1 | scene-advantage |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|scene-advantage` |
^scene-advantage

| dice: 1d1 | quest-mission |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-mission-1`—`dice: [[Random Realities#^data]]\|quest-mission-2` |
^quest-mission

| dice: 1d1 | quest-opposition |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-opposition-1`—`dice: [[Random Realities#^data]]\|quest-opposition-2` |
^quest-opposition

| dice: 1d1 | quest-hindrance |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-hindrance` |
^quest-hindrance

| dice: 1d1 | quest-aid |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-aid` |
^quest-aid

| dice: 1d1 | quest-escalation |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-escalation` |
^quest-escalation

| dice: 1d1 | quest-reward |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-reward` |
^quest-reward

| dice: 1d1 | quest-twist |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-twist` |
^quest-twist

| dice: 1d1 | quest-progress |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-progress` |
^quest-progress

| dice: 1d1 | quest-tension |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|quest-tension` |
^quest-tension

| dice: 1d1 | location-past |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-past` |
^location-past

| dice: 1d1 | location-present |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-present` |
^location-present

| dice: 1d1 | location-descriptor |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-descriptor-1`—`dice: [[Random Realities#^data]]\|location-descriptor-2` |
^location-descriptor

| dice: 1d1 | location-trouble |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-trouble` |
^location-trouble

| dice: 1d1 | location-building |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-building-1`—`dice: [[Random Realities#^data]]\|location-building-2` |
^location-building

| dice: 1d1 | location-influence |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-influence` |
^location-influence

| dice: 1d1 | location-mood |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-mood` |
^location-mood

| dice: 1d1 | location-rumor |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-rumor` |
^location-rumor

| dice: 1d1 | location-seeks |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-seeks` |
^location-seeks

| dice: 1d1 | location-offers |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|location-offers` |
^location-offers

| dice: 1d1 | people-name |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-name-1`—`dice: [[Random Realities#^data]]\|people-name-2`—`dice: [[Random Realities#^data]]\|people-name-3` |
^people-name

| dice: 1d1 | people-disposition |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-disposition-1`—`dice: [[Random Realities#^data]]\|people-disposition-2` |
^people-disposition

| dice: 1d1 | people-role |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-role-1`—`dice: [[Random Realities#^data]]\|people-role-2` |
^people-role

| dice: 1d1 | people-descriptor |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-descriptor` |
^people-descriptor

| dice: 1d1 | people-quirk |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-quirk` |
^people-quirk

| dice: 1d1 | people-drive |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-drive-1`—`dice: [[Random Realities#^data]]\|people-drive-2` |
^people-drive

| dice: 1d1 | people-secret |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-secret` |
^people-secret

| dice: 1d1 | people-seeks |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-seeks` |
^people-seeks

| dice: 1d1 | people-offers |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|people-offers` |
^people-offers

| dice: 1d1 | creature-name |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creature-name-1`—`dice: [[Random Realities#^data]]\|creature-name-2` |
^creature-name

| dice: 1d1 | creature-form |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creature-form-1`—`dice: [[Random Realities#^data]]\|creature-form-2` |
^creature-form

| dice: 1d1 | creature-power |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creature-power` |
^creature-power

| dice: 1d1 | creature-feature |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creature-feature` |
^creature-feature

| dice: 1d1 | creature-action |
| --- | --- |
| 1         | `dice: [[Random Realities#^data]]\|creature-action-1`—`dice: [[Random Realities#^data]]\|creature-action-2` |
^creature-action



# Data

|     | fate-d66 | fate-d4 | fate-d12 | fate-chance            | general-simple | general-complex-1 | general-complex-2 | general-complex-3 | general-abstract-1 | general-abstract-2 | general-intensity        | world-name-1 | world-name-2 | world-aspects-1 | world-aspects-2 | world-inhabitants-1 | world-inhabitants-2 | world-icon-1 | world-icon-2  | world-icon-3 | world-icon-4  | exploration-terrain-1 | exploration-terrain-2 | exploration-ornament-1 | exploration-ornament-2 | exploration-event-1 | exploration-event-2 | exploration-findings-1 | exploration-findings-2 | exploration-icon-1 | exploration-icon-2 | exploration-icon-3 | exploration-icon-4 | creation-purpose | creation-trait             | creation-magic-1 | creation-magic-2 | creation-corruption | creation-icon-1  | creation-icon-2 | creation-icon-3 | creation-icon-4 | scene-challenge-1 | scene-challenge-2 | scene-reaction-1 | scene-reaction-2 | scene-senses-1   | scene-senses-2    | scene-activity          | scene-detail                                          | scene-development                                    | scene-complication                                                | scene-advantage                                                   | quest-mission-1 | quest-mission-2 | quest-opposition-1 | quest-opposition-2 | quest-hindrance        | quest-aid             | quest-escalation          | quest-reward | quest-twist               | quest-progress | quest-tension | location-past | location-present | location-descriptor-1 | location-descriptor-2 | location-trouble          | location-building-1 | location-building-2 | location-influence    | location-mood         | location-rumor      | location-seeks | location-offers | people-name-1 | people-name-2 | people-name-3 | people-disposition-1 | people-disposition-2 | people-role-1 | people-role-2 | people-descriptor | people-quirk        | people-drive-1 | people-drive-2 | people-secret         | people-seeks  | people-offers | creature-name-1 | creature-name-2 | creature-form-1 | creature-form-2 | creature-power   | creature-feature       | creature-action-1 | creature-action-2 |
| --- | -------- | ------- | -------- | ---------------------- | -------------- | ----------------- | ----------------- | ----------------- | ------------------ | ------------------ | ------------------------ | ------------ | ------------ | --------------- | --------------- | ------------------- | ------------------- | ------------ | ------------- | ------------ | ------------- | --------------------- | --------------------- | ---------------------- | ---------------------- | ------------------- | ------------------- | ---------------------- | ---------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ---------------- | -------------------------- | ---------------- | ---------------- | ------------------- | ---------------- | --------------- | --------------- | --------------- | ----------------- | ----------------- | ---------------- | ---------------- | ---------------- | ----------------- | ----------------------- | ----------------------------------------------------- | ---------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- | --------------- | --------------- | ------------------ | ------------------ | ---------------------- | --------------------- | ------------------------- | ------------ | ------------------------- | -------------- | ------------- | ------------- | ---------------- | --------------------- | --------------------- | ------------------------- | ------------------- | ------------------- | --------------------- | --------------------- | ------------------- | -------------- | --------------- | ------------- | ------------- | ------------- | -------------------- | -------------------- | ------------- | ------------- | ----------------- | ------------------- | -------------- | -------------- | --------------------- | ------------- | ------------- | --------------- | --------------- | --------------- | --------------- | ---------------- | ---------------------- | ----------------- | ----------------- |
| 1   | 1.1      | 1       | 1        | Very unlikely — 1 in 6 | Strong No      | Abandon           | Artificial        | Alliance          | Air                | Belief             | Very low, the minimum    | Aer          | bane         | Beasts          | Advanced        | Ancient             | Aliens              | Alien        | Ant           | Bridge       | Anchor        | Ageless               | Bay                   | Aromatic               | Altar                  | Abnormal            | Aberration          | Abundant               | Ally                   | Clear              | Hot                | North              | Sunrise            | Amplification    | Ancient runes inscribed    | Absorb           | Acid             | Aging acceleration  | Animal Skull     | Agriculture     | Bomb            | Amber           | Easy              | Ambush            | Abort            | Advantage        | Animal musk      | Animal echo       | Alchemical experiment   | A character's facial expression or body language      | A choice between pursuing or abandoning a goal       | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Attack          | Ally            | Alien              | Army               | Competing interests    | Advanced technology   | Time is running out       | Access       | Ally's dark history       | Advance        | Aggravate     | Arena         | Academy          | Abandoned             | Arid                  | Ancestral land at risk    | Administration      | Abandoned           | Ancient being         | Aloof disinterest     | Abandoned mine      | Advice         | Adventure       | Aer           | ador          | ael           | Aggressive           | Arguing              | Adventurous   | Acolyte       | Absent-minded     | Animated gestures   | Acceptance     | Ambition       | Ancient curse         | Access        | Advice        | Brak            | ader            | Minuscule       | Amorphous       | Acid spray       | Adhesive secretions    | Attack            | Adaptation        |
| 2   | 1.2      | 2       | 2        | Very unlikely — 1 in 6 | Strong No      | Align             | Beautiful         | Authority         | Barrier            | Blossom            | Very low, the minimum    | Arken        | crest        | Blood           | Concealed       | Arcane              | Angels              | Arch         | Anvil         | Broken Sword | Atom          | Ashen                 | Bog                   | Blooming               | Arch                   | Aggressive          | Animal              | Advanced               | Artefact               | Clear              | Hot                | North              | Sunrise            | Burn             | Bioluminescent organisms   | Amplify          | Ash              | Animal aggression   | Armor            | Amphora         | Bonfire         | Botany          | Easy              | Barrier           | Advance          | Ally             | Berries          | Babbling brook    | Arrival of travelers    | A character's first impression about the scene        | A current context brings about a surprising alliance | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Avoid           | Artifact        | Ancient            | Artifact           | Corrupt authority      | Allies in high places | Rival factions close in   | Ally         | Altered past event        | Ascendancy     | Amplify       | Artifacts     | Arcane secrets   | Abundant              | Barren                | Ancient curse awakens     | Archives            | Ancient             | Arcane academy        | Analytical appraisal  | Ancient ruins       | Alliances      | Archives        | Bael          | aes           | ain           | Aloof                | Building             | Ambitious     | Apprentice    | Adorned           | Boisterous laughter | Adventure      | Ancestry       | Ancient lineage       | Allies        | Aid           | Crux            | akul            | Tiny            | Amphibian       | Berserker rage   | Barbed tail            | Blast             | Agility           |
| 3   | 1.3      | 3       | 3        | Very unlikely — 1 in 6 | Strong No      | Avenge            | Broken            | Burden            | Bond               | Death              | Very low, the minimum    | Bel          | cross        | Bone            | Controlled      | Celestial           | Assassins           | Balance      | Award         | Bubbles      | Battle Axe    | Barren                | Cliffs                | Brittle                | Birds                  | Augmented           | Bandits             | Arcane                 | Blessing               | Clear              | Hot                | North              | Sunrise            | Captivate        | Dark colors and texture    | Animate          | Aura             | Blood thirst        | Astrolabe        | Backpack        | Bottle          | Bracelet        | Easy              | Battle            | Aim              | Balance          | Bitter tang      | Bird call         | Artists at work         | A detail of the local flora                           | A distant ally's plight reaches your ears            | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Battle          | Creature        | Arcane             | Assassin           | Cultural taboo         | Ancient prophecy      | Civilians interfere       | Artifact     | Antagonist familial tie   | Awakening      | Brew          | Battlefield   | Art              | Ancient               | Cold                  | Ancient rights challenged | Art                 | Bustling            | Artisans' collective  | Bustling activity     | Bewitched painting  | Artifacts      | Art             | Bran          | bor           | al            | Ambivalent           | Celebrating          | Betrayed      | Architect     | Athletic          | Constant humming    | Balance        | Anger          | Betrayed ally         | Answers       | Artifacts     | Dran            | alis            | Petite          | Angelic         | Blinding spark   | Bioluminescent spots   | Blind             | Camouflage        |
| 4   | 1.4      | 4       | 4        | Very unlikely — 1 in 6 | Strong No      | Awaken            | Busy              | Celebration       | Chaos              | Debt               | Very low, the minimum    | Bryn         | dale         | City            | Dangerous       | Corrupted           | Automatons          | Balloon      | Banner        | Cage         | Book          | Black                 | Crags                 | Buried                 | Boulder                | Benevolent          | Cavern              | Archaic                | Bones                  | Clear              | Hot                | North              | Sunrise            | Ceremony         | Delicate, lace-like edges  | Attract          | Beast            | Chronic fatigue     | Bee              | Beak            | Brick           | Brain           | Easy              | Chase             | Block            | Barrier          | Blood tang       | Buzzing insects   | Children's playtime     | A lingering scent in the air                          | A distant event foreshadows an upcoming challenge    | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Capture         | Dignitary       | Belligerent        | Beast              | Curse or spell         | Benefactor's funding  | Disguise broken or needed | Blessing     | Antagonist redeemed       | Breakthrough   | Build         | Burial site   | Black market     | Broken                | Colorful              | Bloodlines at war         | Ceremony            | Compact             | Assassins' guild      | Chilling isolation    | Buried secrets      | Artisanship    | Beauty          | Cai           | bri           | am            | Antagonistic         | Cleaning             | Brave         | Artificer     | Bitter            | Elegant posture     | Change         | Atonement      | Blackmail victim      | Assistance    | Connections   | Drax            | amos            | Small           | Aquatic         | Clone self       | Chameleon skin         | Charge            | Coercion          |
| 5   | 1.5      | 1       | 5        | Very unlikely — 1 in 6 | Strong No      | Balance           | Cold              | Community         | Darkness           | Decay              | Very low, the minimum    | Cael         | dor          | Crime           | Declining       | Cursed              | Bandits             | Bamboo       | Bone          | Candelabra   | Broken Arrow  | Blessed               | Desert                | Burning                | Bridge                 | Bleak               | Chasm               | Benevolent             | Cache                  | Clear              | Warm               | North              | Morning            | Command          | Elegant filigree details   | Awaken           | Blood            | Disintegration      | Boomerang        | Beetle          | Broken Egg      | Burning Heart   | Easy              | Competition       | Break            | Chance           | Briny odor       | Chiming bells     | Clandestine gambling    | A nearby conversation or interaction                  | A found object leads to new theories                 | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Compete         | Enemy           | Bloodthirsty       | Clan               | Difficult terrain      | Cryptic key           | Unforeseen consequences   | Fame         | Artifact's sentience      | Complication   | Calm          | Capital       | Courthouse       | Bustling              | Crumbling             | Broken promises           | Commerce            | Controversial       | Beast pack alpha      | Contagious enthusiasm | Corrupted official  | Champions      | Contracts       | Cal           | cur           | ant           | Bold                 | Communicating        | Cunning       | Artisan       | Brooding          | Exaggerated bow     | Control        | Betrayal       | Broken vow            | Attention     | Cover         | Ghast           | aris            | Stocky          | Avian           | Crystal shield   | Corrosive saliva       | Constrict         | Cunning           |
| 6   | 1.6      | 2       | 6        | Unlikely — 2 in 6      | No             | Blend             | Damaged           | Corruption        | Decline            | Dispute            | Low, less than expected  | Drak         | eon          | Crystal         | Disputed        | Decaying            | Demons              | Baobab       | Broken Shield | Canyon       | Broken Planet | Blighted              | Dunes                 | Colorful               | Cairn                  | Bloody              | Construct           | Broken                 | Carvings               | Clear              | Warm               | Northeast          | Morning            | Containment      | Embedded precious stones   | Bind             | Bone             | Elemental imbalance | Boot             | Bell            | Cauldron        | Butterfly       | Normal            | Contest           | Challenge        | Control          | Burning wood     | Chirping crickets | Courier's haste         | A notable ornament or detail in the environment       | A local dispute draws you into its fold              | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Conquer         | Environment     | Chaotic            | Corporation        | Espionage or sabotage  | Detailed map          | Conflicting objectives    | Favor        | Belief challenged         | Converge       | Cascade       | Cataclysm     | Crafting         | Contested             | Dense                 | Caught amidst strife      | Communication       | Cozy                | City watch commander  | Deliberate avoidance  | Cursed statue       | Creatures      | Craftsmanship   | Dae           | dar           | ar            | Cautious             | Crafting             | Cursed        | Assassin      | Charismatic       | Faded scars         | Discovery      | Challenge      | Buried treasure       | Blessing      | Creativity    | Ghor            | astar           | Sturdy          | Bear            | Darkness wrap    | Elongated neck         | Control           | Deception         |
| 7   | 2.1      | 3       | 7        | Unlikely — 2 in 6      | No             | Breach            | Dark              | Courage           | Earth              | Dominion           | Low, less than expected  | Dyr          | far          | Cyber           | Dominant        | Desolate            | Dinosaurs           | Broken Link  | Burst         | Cloak        | Broken Skull  | Broken                | Fells                 | Colossal               | Caves                  | Clouded             | Creature            | Constructed            | Clue                   | Clear              | Warm               | Northeast          | Morning            | Crafting         | Enigmatic symbols etched   | Channel          | Chaos            | Enveloping shadows  | Broken Heart     | Boat            | Chalice         | Compass         | Normal            | Crafting          | Climb            | Courage          | Citrus aroma     | Coins clinking    | Craftsmanship display   | A subtle, elusive sound permeating the background     | A message from afar alters your plans                | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Contact         | Event           | Colossal           | Creature           | Ethical dilemma        | Divine blessing       | Moral dilemma             | Guidance     | Dead character lives      | Crossroads     | Decrease      | Colony        | Crime            | Corrupted             | Expansive             | Celebration at risk       | Craftsmanship       | Foreboding          | Council of elders     | Diplomatic formality  | Disappearing ships  | Diplomacy      | Cuisine         | El            | dul           | as            | Cheerful             | Drawing              | Desperate     | Cartographer  | Compassionate     | Fidgety hands       | Dominance      | Curiosity      | Clandestine affair    | Companionship | Cure          | Glac            | ater            | Bony            | Canine          | Earthquake       | Enormous pincers       | Crush             | Distraction       |
| 8   | 2.2      | 4       | 8        | Unlikely — 2 in 6      | No             | Break             | Defiled           | Creature          | Edge               | Dream              | Low, less than expected  | Eld          | fell         | Death           | Emerging        | Dreaming            | Dragons             | Burning Tree | Cactus        | Comet        | Cannon        | Cursed                | Fen                   | Floating               | Circle                 | Collapsing          | Disease             | Cryptic                | Footprints             | Partly Cloudy      | Warm               | Northeast          | Morning            | Crush            | Ethereal transparency      | Conceal          | Dream            | Ethereal detachment | Chariot          | Bust            | Cyclone         | Direction       | Normal            | Debate            | Collide          | Damage           | Creamy scent     | Crackling fire    | Dance rehearsal         | A unique architectural feature or design element      | A mysterious past event becomes crucially clear      | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Corrupt         | Experiment      | Corrupted          | Criminal           | Fierce competition     | Elite mercenary       | Incomplete information    | Healing      | Decoy goal                | Dead end       | Deepen        | Coronation    | Crossroads       | Cursed                | Extravagant           | Clan feud escalates       | Culture             | Fortified           | Divine entity         | Eerie stillness       | Eldritch tome       | Energy         | Culture         | Eri           | est           | ast           | Confident            | Drinking             | Disgraced     | Courier       | Corpulent         | Flamboyant attire   | Enlightenment  | Despair        | Criminal past         | Contacts      | Deception     | Grak            | aug             | Delicate        | Construct       | Energy beam      | Exoskeleton frame      | Curse             | Fear              |
| 9   | 2.3      | 1       | 9        | Unlikely — 2 in 6      | No             | Channel           | Delicate          | Danger            | Exposure           | Fame               | Low, less than expected  | Elyr         | ford         | Depths          | Essential       | Eldritch            | Elementals          | Candle       | Coffin        | Creature     | Chemistry     | Dead                  | Fjords                | Frosted                | Cobwebs                | Corrupted           | Earthquake          | Damaged                | Fungi                  | Partly Cloudy      | Warm               | Northeast          | Morning            | Defense          | Flickering effect          | Control          | Earth            | Fire touch          | Closed Eye       | Chaos           | Drop            | Ear             | Normal            | Diplomacy         | Combat           | Defense          | Dried herbs      | Creaking wood     | Desperate chase         | A whispered conversation or hushed tones              | A new character enters the scene, motives unclear    | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Create          | Group           | Deceptive          | Cult               | Forbidden knowledge    | Essential documents   | Resources are scarce      | Honor        | Double agent revealed     | Descent        | Diminish      | Discovery     | Cuisine          | Decaying              | Foggy                 | Command under scrutiny    | Defense             | Functional          | Elected official      | Ethereal mystique     | Enchanted forest    | Exchange       | Defenses        | Fal           | fer           | el            | Cooperative          | Dying                | Dishonored    | Diplomat      | Delicate          | Frequent sighing    | Equality       | Duty           | Cursed object         | Directions    | Distraction   | Grim            | avor            | Plump           | Crustacean      | Fear aura        | Ferocious roar         | Defend            | Guile             |
| 10  | 2.4      | 2       | 10       | Unlikely — 2 in 6      | No             | Clash             | Empty             | Deception         | Fate               | Feeling            | Low, less than expected  | Evin         | gard         | Desert          | Evident         | Enchanted           | Fairies             | Cave         | Column        | Cut Hand     | Chimp         | Deadly                | Forest                | Haunted                | Craters                | Creepy              | Elemental           | Dangerous              | Garden                 | Partly Cloudy      | Mild               | East               | Morning            | Detection        | Floating elements          | Create           | Flames           | Frostbite           | Clover           | Chest           | Expansion       | Exit            | Normal            | Disaster          | Concentrate      | Determination    | Dry bark         | Distant battle    | Elders' wisdom          | A wide shot of the landscape                          | A new character holds the key to a pending mystery   | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Decipher        | Heritage        | Devouring          | Curse              | Forced secrecy         | Expert navigator      | Key abilities useless     | Influence    | Enemy's strong return     | Detour         | Dissipate     | Drought       | Embassy          | Desolate              | Gleaming              | Community pillar falls    | Detention           | Futuristic          | Elemental warden      | Festive atmosphere    | Forbidden library   | Expansion      | Directions      | Fin           | gan           | elle          | Curious              | Escaping             | Elderly       | Exile         | Discreet          | Gentle drawl        | Excellence     | Empathy        | Cursed wealth         | Endorsement   | Entry         | Krax            | azun            | Sinuous         | Crystal         | Fire breath      | Glowing fur            | Dissolve          | Imitation         |
| 11  | 2.5      | 3       | 11       | Unlikely — 2 in 6      | No             | Conjure           | Enormous          | Destiny           | Fire               | Fellowship         | Low, less than expected  | Fen          | garde        | Faith           | Evolving        | Ethereal            | Gargoyles           | Cornucopia   | Connection    | Eclipse      | Cycle         | Deep                  | Glacier               | Iridescent             | Crystals               | Deceitful           | Explorer            | Dead                   | Gems                   | Partly Cloudy      | Mild               | East               | Morning            | Energizing       | Fluid, organic shapes      | Curse            | Fog              | Gravity distortion  | Coin             | Compass         | Fingerprint     | Flower          | Normal            | Duel              | Consolidate      | Environment      | Earthy moss      | Distant thunder   | Enthralling performance | A zoom-in or close-up on a significant detail         | A new threat puts an ally in danger                  | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Defend          | Idea            | Dissident          | Disaster           | Hidden agendas         | Forgotten hero        | Trust is impossible       | Insight      | Event was simulation      | Discovery      | Ebb           | Enlightenment | Entertainment    | Diverse               | Glimmering            | Continuous enigma         | Diplomacy           | Grandiose           | Forest guardian       | Gentle melancholy     | Forbidden magic     | Freedom        | Education       | Gal           | gil           | en            | Defensive            | Exploring            | Experienced   | Farmer        | Elegant           | Haunting gaze       | Fame           | Envy           | Dangerous addiction   | Equipment     | Expertise     | Krell           | ector           | Lithe           | Daemonic        | Flame aura       | Haunting melody        | Distract          | Improvisation     |
| 12  | 2.6      | 4       | 12       | Unlikely — 2 in 6      | No             | Connect           | Exotic            | Disaster          | Force              | Freedom            | Low, less than expected  | Fyr          | glen         | Fire            | Extinct         | Fabled              | Ghosts              | Crate        | Constellation | Fang         | Dagger        | Desolate              | Groves                | Isolated               | Flames                 | Desolate            | Fey                 | Decaying               | Lair                   | Partly Cloudy      | Mild               | East               | Morning            | Expose           | Fractal-inspired motifs    | Destroy          | Glass            | Ground trembling    | Crystal          | Coral           | Floating        | Heat            | Normal            | Endurance         | Coordinate       | Fear             | Floral perfume   | Eerie melody      | Frenzied construction   | An interesting piece of clothing or accessory         | A personal challenge that test your resolve          | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Deliver         | Information     | Envious            | Doppelganger       | Identity concealment   | Forgotten lore        | Authority overstepped     | Key          | False victory revealed    | Divergence     | Echo          | Exodus        | Farm             | Enchanted             | High                  | Corrupt knowledge         | Education           | Guarded             | Guildmaster           | Guarded curiosity     | Forgotten graveyard | Guidance       | Enchantments    | Har           | hes           | end           | Detached             | Guarding             | Fearless      | Forger        | Energetic         | Hushed whispers     | Family         | Faith          | Deserted duty         | Excitement    | Gear          | Kron            | egor            | Medium          | Draconic        | Ice shards       | Iridescent feathers    | Dodge             | Ingenuity         |
| 13  | 3.1      | 1       | 1        | Unlikely — 2 in 6      | No             | Control           | Exquisite         | Disease           | Illusion           | Greed              | Low, less than expected  | Ghor         | grove        | Fists           | Forbidden       | Fiery               | Giants              | Dove         | Crown         | Fist         | Dead Tree     | Dim                   | Heath                 | Lifeless               | Flowers                | Doomed              | Flood               | Depleted               | Map                    | Partly Cloudy      | Mild               | East               | Afternoon          | Foresight        | Geometric precision        | Diminish         | Gravity          | Hallucinations      | Cubes            | Crossbow        | Gauntlet        | Horn            | Normal            | Enigma            | Cover            | Ferocity         | Fresh rain       | Eerie silence     | Grand celebration       | An overhead or bird's-eye view of the area            | A positive twist opens a door previously closed      | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Destroy         | Innocent        | Fallen             | Elemental          | Innocents in danger    | Ghostly guide         | Weaknesses exploited      | Knowledge    | Foe's resurrection        | Enlightenment  | Envelop       | Founding      | Festival         | Exposed               | Icy                   | Disappearances            | Energy              | Hidden              | High clergy           | Heavy despair         | Haunted mansion     | Healing        | Enlightenment   | Is            | jon           | eon           | Dismissive           | Healing              | Fledgling     | Guard         | Enigmatic         | Immaculate nails    | Freedom        | Fear           | Double life           | Guidance      | Guidance      | Lash            | ellon           | Athletic        | Elemental       | Illusions        | Ivory tusks            | Enchant           | Instinct          |
| 14  | 3.2      | 2       | 2        | 50/50 — 3 in 6         | Weak No        | Create            | Fearful           | Doubt             | Inertia            | Hate               | Average, the expected    | Hal          | heim         | Frontier        | Fragmented      | Forgotten           | Gladiators          | Drought      | Deal          | Fossil       | Diamond       | Dismal                | Heights               | Living                 | Fossils                | Enraged             | Fog                 | Empty                  | Message                | Partly Cloudy      | Mild               | East               | Afternoon          | Freeze           | Gleaming metallic finish   | Dispel           | Ice              | Insatiable hunger   | Ectoplasm        | Crystal Ball    | Golem           | Idea            | Normal            | Fight             | Deceive          | Focus            | Fresh soil       | Explosion         | Grim execution          | An unexpected movement or action                      | A remote event ties back to a character's past       | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Discover        | Knowledge       | Fanatical          | Entity             | Language barrier       | Guardian beast        | Uneasy alliance           | Land         | Forbidden love revealed   | Exposition     | Escalate      | Gold rush     | Garrison         | Forgotten             | Low                   | Dwindling supplies        | Entertainment       | Historic            | Industry leader       | Immediate camaraderie | Hidden laboratory   | Ingredients    | Festivities     | Jor           | kel           | es            | Distrustful          | Hiding               | Foolish       | Guide         | Flashy            | Impeccable gloves   | Growth         | Greed          | Escaped convict       | Healing       | Haven         | Mal             | emon            | Slender         | Faerie          | Inferno swirl    | Membrane wings         | Engulf            | Intimidation      |
| 15  | 3.3      | 3       | 3        | 50/50 — 3 in 6         | Weak No        | Decipher          | Forgotten         | Duty              | Light              | Health             | Average, the expected    | Hyr          | hold         | Gear            | Grand           | Forsaken            | Hunters             | Feather      | Door          | Ghost        | Diving        | Dry                   | Hills                 | Lost                   | Insects                | Ethereal            | Fortress            | Ephemeral              | Omen                   | Partly Cloudy      | Cold               | Southeast          | Afternoon          | Gathering        | Imposing structure         | Disrupt          | Light            | Insects swarming    | Floral           | Die             | Hammer          | Lightning       | Normal            | Hardship          | Deflect          | Impulse          | Freshy herbal    | Fabric reap       | Harvest season          | The ambient noise level                               | A resource thought lost is recovered                 | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Eliminate       | Leader          | Ferocious          | Environment        | Legal restrictions     | Hidden vault          | Sinister intentions       | Legacy       | Forced nemesis alliance   | Foreshadow     | Hover         | Great fire    | Gemstones        | Forsaken              | Lush                  | Enemies approaching       | Gathering           | Illuminated         | Labor union           | Infectious joy        | Hidden treasure     | Innovation     | Formulas        | Ker           | kyr           | et            | Eager                | Instructing          | Gifted        | Healer        | Generous          | Ink-stained fingers | Healing        | Guilt          | Exiled royalty        | Information   | Influence     | Mord            | entor           | Rugged          | Feline          | Lava spew        | Multiple eyes          | Evade             | Knowledge         |
| 16  | 3.4      | 4       | 4        | 50/50 — 3 in 6         | Weak No        | Defeat            | Fragile           | Faction           | Loss               | Heritage           | Average, the expected    | Kal          | jorn         | Gods            | Influential     | Haunted             | Investigators       | Fetus        | Fence         | Horseshoe    | Dragon        | Eerie                 | Hollows               | Loud                   | Leaves                 | Exposed             | Giant               | Fragile                | Passage                | Cloudy             | Cold               | Southeast          | Afternoon          | Guidance         | Frosted appearance         | Divide           | Memory           | Invisibility        | Gazelle          | Division        | Horse           | Lock            | Hard              | Hindrance         | Delve            | Instinct         | Metallic rust    | Fluttering wings  | Hasty abduction         | The angle from which the scene is observed            | A significant clue is discovered                     | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Escape          | Legend          | Hostile            | Experiment         | Limited information    | Infiltrated agent     | Powerful obstruction      | Magic        | Game-changing sacrifice   | Fragmentation  | Increase      | Industry      | Guildhall        | Grim                  | Majestic              | Energy core unstable      | Healing             | Imposing            | Local magistrate      | Keen eagerness        | Immortal lord       | Insight        | Goods           | Kyl           | lir           | ian           | Enthusiastic         | Investigating        | Honorable     | Herbalist     | Graceful          | Intricate braids    | Immortality    | Hate           | Fabricated heroism    | Inspiration   | Insight       | Neph            | eon             | Lean            | Fungus          | Lightning bolt   | Multiple limbs         | Explode           | Magic             |
| 17  | 3.5      | 1       | 5        | 50/50 — 3 in 6         | Weak No        | Discover          | Free              | Family            | Matter             | Home               | Average, the expected    | Lumin        | lund         | Ice             | Integral        | Hidden              | Knights             | Flame        | Galaxy        | Jester       | Dragonfly     | Fallen                | Jungle                | Luminous               | Mist                   | Imposing            | Graveyard           | Illusory               | Path                   | Cloudy             | Cold               | Southeast          | Afternoon          | Healing          | Interlocking assembly      | Echo             | Metal            | Light dimming       | Helix            | Esoteric        | Hourglass       | Map             | Hard              | Hunting           | Destroy          | Maneuver         | Minty breeze     | Footsteps         | Healers at service      | The background music or sounds                        | A significant step toward a key objective            | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Expel           | Message         | Imposing           | Faction            | Magic protection       | Insider information   | False crucial intel       | Pardon       | Greater threat unveiled   | Harbinger      | Infect        | Inquisition   | Harbor           | Haunted               | Murky                 | Epidemic outbreak         | History             | Inviting            | Merchant guild        | Lingering sorrow      | Lost language       | Inspiration    | Harmony         | Lor           | lon           | ias           | Friendly             | Laughing             | Humble        | Hermit        | Illustrious       | Lavish jewelry      | Innovation     | Honor          | Faked death           | Medicine      | Instructions  | Nox             | ern             | Bulky           | Geometrical     | Magnetic pull    | Multiple mouths        | Feint             | Manipulation      |
| 18  | 3.6      | 2       | 6        | 50/50 — 3 in 6         | Weak No        | Dwell             | Furious           | Fear              | Maze               | Innocence          | Average, the expected    | Lyr          | mark         | Magic           | Isolated        | Invincible          | Lycanthropes        | Fox          | Gargoyle      | Key          | Gear          | Far                   | Lake                  | Mighty                 | Monolith               | Infested            | Guardian            | Lush                   | Person                 | Cloudy             | Cold               | Southeast          | Afternoon          | Illumination     | Intricate floral patterns  | Encase           | Mind             | Luck drain          | Horn Helmet      | Eye             | Keyhole         | Music           | Hard              | Infiltration      | Dodge            | Object           | Musty books      | Hammering beat    | Hunt on the trail       | The condition of buildings or objects                 | A sudden change in the environment hinders progress  | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Explore         | Object          | Insidious          | Flora              | Moral conflict         | Intercepted message   | Necessary reversal        | Passage      | Hidden enemy unveiled     | Impasse        | Intermittent  | Lost city     | Hospitality      | Hidden                | Natural               | Exile seeks revenge       | Hospitality         | Majestic            | Military general      | Mysterious allure     | Missing heirloom    | Intelligence   | Herbs           | Lys           | mir           | iel           | Guarded              | Listening            | Legendary     | Hunter        | Impassioned       | Lopsided grin       | Justice        | Hope           | Forbidden knowledge   | Money         | Intuition     | Rax             | inth            | Compact         | Humanoid        | Mind blast       | Multiple rows of teeth | Flank             | Observation       |
| 19  | 4.1      | 3       | 7        | 50/50 — 3 in 6         | Weak Yes       | Eliminate         | Glorious          | Hardship          | Movement           | Intrigue           | Average, the expected    | Myr          | mire         | Monsters        | Legendary       | Lost                | Mechas              | Globe        | Holding       | Lighthouse   | Gemstone      | Forgotten             | Lowland               | Murky                  | Mushrooms              | Invisible           | Horror              | Magical                | Plants                 | Cloudy             | Cold               | South              | Afternoon          | Judgement        | Liquid, flowing lines      | Energize         | Plant            | Magic depletion     | Lizard Paw       | Fountain        | Log             | Origami         | Hard              | Interaction       | Endure           | Opening          | Oily stench      | Howling wind      | Insistent beggar        | The contrast between light and shadow                 | A trap is sprung                                     | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Face            | Organization    | Merciless          | Ghost              | Necessary sacrifice    | Legendary spell       | Decipher message          | Peace        | Hidden society's rise     | Interlude      | Lighten       | Magic         | Library          | Infested              | Opulent               | Fickle alliances sour     | Innovation          | Minimalist          | Monarch heir          | Neutral observation   | Mysterious lights   | Knowledge      | History         | Mar           | mon           | il            | Helpful              | Meditating           | Lost          | Informant     | Impulsive         | Lost stare          | Knowledge      | Ideology       | Forbidden love        | Opportunity   | Knowledge     | Shard           | iris            | Graceful        | Insectoid       | Mirage creation  | Multiple tentacles     | Grapple           | Patience          |
| 20  | 4.2      | 4       | 8        | 50/50 — 3 in 6         | Weak Yes       | Enrich            | Grotesque         | Harmony           | Nature             | Knowledge          | Average, the expected    | Noc          | moor         | Moon            | Limited         | Mysterious          | Merfolk             | Harpy        | Knight        | Maze         | Harp          | Forsaken              | Marsh                 | Overgrown              | Nests                  | Lost                | Hunter              | Malevolent             | Potion                 | Cloudy             | Snow               | South              | Afternoon          | Lure             | Luminous glow              | Enhance          | Plasma           | Memory loss         | Magnifying Glass | Gaze            | Lute            | Perfume         | Hard              | Interrogation     | Force            | Position         | Peppery scent    | Jangling keys     | Intense bartering       | The density or sparseness of vegetation               | Ambiguity arises from a cryptic message              | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Find            | Path            | Misguided          | Invader            | Oath or vow            | Local guide           | Dubious aid needed        | Position     | Justified villain actions | Manifestation  | Linger        | Migration     | Market           | Invaded               | Overgrown             | Hazardous ritual          | Justice             | Modern              | Monastic order        | Ominous foreboding    | Mystic portal       | Languages      | Hospitality     | Mor           | nis           | in            | Hostile              | Nurturing            | Loyal         | Laborer       | Intuitive         | Melodic voice       | Legacy         | Immunity       | Forged documents      | Pardon        | Labor         | Skor            | itar            | Lanky           | Jellyfish       | Mist form        | Noxious stench         | Growl             | Persistence       |
| 21  | 4.3      | 1       | 9        | 50/50 — 3 in 6         | Weak Yes       | Evade             | Humble            | History           | Origin             | Labor              | Average, the expected    | Oryn         | nir          | Myth            | Marginal        | Mystic              | Mobsters            | Imp          | Lotus         | Meteorite    | Inkwell       | Frozen                | Meadows               | Pale                   | Orchard                | Malevolent          | Mine                | Misleading             | Relic                  | Cloudy             | Snow               | South              | Sunset             | Memorial         | Non-reflective texture     | Freeze           | Poison           | Metal rusting       | Mouse            | Gold            | Paintbrush      | Pulse           | Hard              | Investigation     | Grab             | Posture          | Pine needles     | Laughter          | Knightly duel           | The feel of a surface to the touch                    | An elusive secret is hinted at                       | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Invade          | Phenomenon      | Poisonous          | Leviathan          | Political intrigue     | Magical artifact      | Quest's true nature       | Protection   | Key character falls       | Meander        | Loosen        | Mine          | Martial arts     | Isolated              | Polluted              | Heirloom vanishes         | Knowledge           | Monumental          | Necromancer           | Palpable tension      | Rebel hideout       | Materials      | Immunity        | Nae           | orn           | ir            | Indifferent          | Observing            | Mysterious    | Leader        | Inventive         | Mismatched eyes     | Mastery        | Love           | Illegitimate child    | Passion       | Mentorship    | Skul            | ixion           | Rotund          | Lizard          | Nature's command | Prehensile tail        | Intimidate        | Resilience        |
| 22  | 4.4      | 2       | 10       | 50/50 — 3 in 6         | Weak Yes       | Focus             | Illusory          | Honor             | Passage            | Language           | Average, the expected    | Pher         | oria         | Occult          | Modest          | Mythical            | Monks               | Knot         | Musket        | Palm Tree    | Lantern       | Grim                  | Moor                  | Parched                | Pathways               | Marked              | Monster             | Natural                | Resources              | Foggy              | Snow               | South              | Sunset             | Navigation       | Minimalist design          | Ignite           | Portal           | Mist thickening     | Mushroom         | Healing         | Pickaxe         | Ring            | Hard              | Menace            | Help             | Power            | Powdery perfume  | Low hum           | Merchant negotiation    | The general demeanor of the people                    | An event offers a brief respite                      | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Investigate     | Place           | Possessed          | Noble              | Prophecy or destiny    | Master craftsman      | Mysterious phenomenon     | Relic        | Lost power returns        | Merge          | Mellow        | Monastery     | Medicine         | Mystical              | Pristine              | Invisible killers         | Magic               | Mysterious          | Noble court           | Peaceful solitude     | Royal scandal       | Partnerships   | Inns            | Nor           | pel           | is            | Inquisitive          | Painting             | Noble         | Mercenary     | Jovial            | Monotone speech     | Peace          | Loyalty        | Illicit trade         | Path          | Motivation    | Slith           | odox            | Robust          | Metallic        | Necrotic touch   | Prehensile tongue      | Lash              | Sacrifice         |
| 23  | 4.5      | 3       | 11       | 50/50 — 3 in 6         | Weak Yes       | Guard             | Intense           | Hope              | Path               | Law                | Average, the expected    | Pyre         | peak         | Peaks           | Non-existent    | Nomadic             | Mutants             | Letter       | Night         | Paw          | Leech         | Holy                  | Mounds                | Phantasmal             | Pillars                | Mechanical          | Pack                | Obscured               | Scraps                 | Foggy              | Snow               | South              | Sunset             | Observation      | Mirror-polished shine      | Infuse           | Shadows          | Mutation            | Panther          | Mace            | Portal          | Safebox         | Hard              | Mystery           | Impact           | Precision        | Pungent sweat    | Metal clang       | Meticulous repair       | The interplay between natural and artificial elements | An old wound resurfaces at the worst time            | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Kill            | Power           | Predatory          | Phenomenon         | Relatives in danger    | Nature spirit         | Sacrificial decision      | Respect      | Love transcends rivalry   | Momentum       | Peak          | Palace        | Military         | Occupied              | Rocky                 | Land under darkness       | Memorial            | Natural             | Oracle                | Quiet anticipation    | Sealed gate         | Peace          | Libraries       | Oll           | quir          | isto          | Interested           | Patrolling           | Outcast       | Monk          | Melancholic       | Nervous twitch      | Power          | Necessity      | Lost heirloom         | Protection    | Passage       | Sorn            | ogen            | Large           | Octopus         | Paralysis sting  | Pungent aroma          | Lunge             | Scheming          |
| 24  | 4.6      | 4       | 12       | Likely — 4 in 6        | Yes            | Harness           | Lethal            | Leader            | Peace              | Legacy             | High, more than expected | Quor         | pier         | Power           | Outdated        | Primeval            | Pilots              | Lizard       | Planet        | Potion       | Mirror        | Impassable            | Mountains             | Pulsating              | Pit                    | Primitive           | Poison              | Preserved              | Seeds                  | Foggy              | Snowstorm          | Southwest          | Sunset             | Passage          | Muted, earthy tones        | Manipulate       | Skin             | Necrosis            | Poison Apple     | Magic Eye       | Prosthetic      | Sand            | Hard              | Negotiation       | Intensify        | Pride            | Rotten eggs      | Muffled talk      | Pilgrims' devotion      | The overall mood and atmosphere                       | An unforeseen ally offers assistance                 | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Negotiate       | Principle       | Rampaging          | Pirates            | Requires specific tool | Network of spies      | Erratic transformation    | Sanctuary    | Manipulated conflict      | Quandary       | Permeate      | Pilgrimage    | Nature           | Peaceful              | Rugged                | Marauders attacks         | Observation         | Opulent             | Pirate captain        | Reserved skepticism   | Secret entrance     | Preservation   | Lore            | Ori           | ren           | ith           | Inviting             | Planning             | Poor          | Pilgrim       | Menacing          | Peculiar accent     | Protection     | Nostalgia      | Lost sibling          | Provisions    | Resources     | Strix           | olith           | Muscular        | Ooze            | Poison fangs     | Reflective skin        | Maneuver          | Sorcery           |
| 25  | 5.1      | 1       | 1        | Likely — 4 in 6        | Yes            | Hold              | Lonely            | Opportunity       | Plenty             | Life               | High, more than expected | Rael         | quill        | Punk            | Profane         | Rebel               | Pirates             | Mask         | Scepter       | Raven        | Mountain      | Jagged                | Plains                | Rugged                 | Pond                   | Raging              | Predator            | Radiant                | Shelter                | Drizzle            | Snowstorm          | Southwest          | Evening            | Projecting       | Mystic, swirling patterns  | Phase            | Sound            | Petrification       | Puzzle           | Nose            | Spear           | Seashell        | Hard              | Obstacle          | Invest           | Reach            | Rotten fruits    | Pattering rain    | Priests in prayer       | The patterns on clothing or objects                   | Closure brings about a bittersweet revelation        | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Overcome        | Prophecy        | Ruthless           | Prophecy           | Resource monopoly      | Powerful weapon       | Paths intertwined         | Secret       | Memory's deception        | Regress        | Plateau       | Piracy        | Observatory      | Prosperous            | Rustic                | Mission under threat      | Recreation          | Ornate              | Prophet               | Serene calmness       | Secret societies    | Protection     | Luxury          | Phe           | ril           | ix            | Open                 | Reading              | Reclusive     | Pirate        | Pensive           | Perpetual smirk     | Redemption     | Obsession      | Masked vigilante      | Refuge        | Sanctuary     | Sal             | onir            | Hefty           | Plant           | Psychic scream   | Retractable claws      | Mimic             | Speed             |
| 26  | 5.2      | 2       | 2        | Likely — 4 in 6        | Yes            | Initiate          | Mundane           | Phenomenon        | Progress           | Love               | High, more than expected | Rune         | rath         | Ruins           | Rare            | Renegade            | Psychics            | Monster      | Skull         | Saber        | Obelisk       | Lush                  | Prairie               | Sharp                  | River                  | Roaming             | Quicksand           | Rare                   | Sign                   | Drizzle            | Snowstorm          | Southwest          | Evening            | Reflection       | Natural wood grain         | Purify           | Specter          | Plant decay         | Slime            | Pendulum        | Steak           | Seedling        | Very hard         | Persuasion        | Knock down       | Resource         | Saltwater breeze | Predator growl    | Scholarly dispute       | The position of the sun or moon, or the time of day   | Fortune shifts with a change of heart                | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Protect         | Relationship    | Savage             | Raiders            | Restricted access      | Protective gear       | Covert manipulation       | Skill        | Past defeat is key        | Reroute        | Recede        | Plague        | Occult           | Protected             | Shadowy               | Outsider sparks conflict  | Refuge              | Overgrown           | Rebel commander       | Sincere concern       | Silent plague       | Reforms        | Marvels         | Quin          | ser           | ol            | Optimistic           | Relaxing             | Renowned      | Ranger        | Philosophical     | Piercing squint     | Renown         | Passion        | Mysterious benefactor | Relief        | Service       | Thal            | oroth           | Tall            | Primate         | Regeneration     | Retractable trunk      | Paralyze          | Stealth           |
| 27  | 5.3      | 3       | 3        | Likely — 4 in 6        | Yes            | Manipulate        | Natural           | Possession        | Protection         | Pain               | High, more than expected | Sor          | ridge        | Science         | Receding        | Ruined              | Sages               | Pentagram    | Snail         | Scythe       | Octopus       | Misty                 | Scarps                | Stoney                 | Rodents                | Sacred              | Ruins               | Rich                   | Spell                  | Drizzle            | Breeze             | Southwest          | Evening            | Research         | Opulent gold leaf accents  | Reflect          | Spirit           | Plant growth        | Spring           | Pincer          | Steam           | Shell           | Very hard         | Puzzle            | Lose             | Senses           | Sharp chemics    | River rumble      | Secretive rendezvous    | The posture of a character                            | News of an advancing threat alters priorities        | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Pursue          | Resource        | Shadowy            | Rival              | Rival claim            | Rebel leader          | Dark secrets unveiled     | Spell        | Powerful ally             | Respite        | Ripple        | Prison        | Quarry           | Radiant               | Small                 | Plague's spread           | Research            | Pristine            | Royal family          | Solemn respect        | Stolen artifact     | Reinforcements | Navigation      | Rai           | tir           | on            | Pessimistic          | Repairing            | Respected     | Sage          | Placid            | Restless legs       | Respect        | Pride          | Powerful enemy        | Safety        | Skill         | Thar            | osis            | Broad           | Rodent          | Sandstorm        | Sharp scales           | Parry             | Strategy          |
| 28  | 5.4      | 4       | 4        | Likely — 4 in 6        | Yes            | Navigate          | New               | Sanctuary         | Rupture            | Price              | High, more than expected | Syl          | shore        | Sea             | Recent          | Sacred              | Scientists          | Pointed Ear  | Snowglobe     | Shield       | Owl           | Petrified             | Sea                   | Sturdy                 | Roots                  | Serene              | Spirit              | Sealed                 | Supplies               | Drizzle            | Breeze             | West               | Evening            | Rest             | Prismatic reflections      | Regenerate       | Stone            | Poisoning           | Stalactite       | Private         | Stomach         | Smoke           | Very hard         | Quarrel           | Oppose           | Speed            | Smoky ash        | Rushing waterfall | Sentry duty             | The presence of a specific animal or creature         | Someone takes a surprising and impactful action      | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Recover         | Secret          | Sinister           | Ruler              | Scarce resources       | Revealed weakness     | Past whispers             | Talent       | Prophecy's true meaning   | Retrace        | Simmer        | Rebellion     | Refuge           | Ruined                | Sparse                | Poisonous extraction      | Residence           | Reflective          | Scholarly order       | Soothing harmony      | Sunken city         | Relics         | Passages        | Syl           | tor           | or            | Reluctant            | Resting              | Retired       | Sailor        | Pragmatic         | Rhythmic tapping    | Retribution    | Regret         | Schemed revolt        | Schemes       | Solace        | Throm           | oth             | Ponderous       | Slug            | Shadow walk      | Spiky shell            | Pounce            | Strength          |
| 29  | 5.5      | 1       | 5        | Likely — 4 in 6        | Yes            | Protect           | Old               | Secret            | Scarcity           | Relationship       | High, more than expected | Thra         | spear        | Shadow          | Resurging       | Savage              | Soldiers            | Pyramid      | Submarine     | Sun          | Railroad      | Scorching             | Steppe                | Thorny                 | Shrine                 | Silent              | Stampede            | Spoiled                | Tools                  | Rain               | Breeze             | West               | Evening            | Ritual           | Rich, deep patina          | Repel            | Thunder          | Silence             | Stars            | Scroll          | Target          | Stake           | Very hard         | Race              | Penetrate        | Strategy         | Spiced incense   | Rustling leaves   | Soldiers on march       | The prevailing hues and tones of the scene            | Someone's action forces you into defense             | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Rescue          | Symbol          | Supernatural       | Saboteur           | Shifting allegiances   | Safe haven            | Natural disaster          | Technique    | Secret alliance exposed   | Retreat        | Slow          | Renaissance   | Sanctuary        | Sacred                | Sprawling             | Predator's hung           | Rest                | Sacred              | Social reformer       | Stark bleakness       | Unbreakable curse   | Routes         | Refuge          | Tal           | urn           | os            | Resentful            | Running              | Ruthless      | Scholar       | Resilient         | Sardonic chuckle    | Revolution     | Rivalry        | Sinister pact         | Secrets       | Stories       | Tyr             | othek           | Burly           | Snake           | Shape shifting   | Spiraling horns        | Rip               | Subterfuge        |
| 30  | 5.6      | 2       | 6        | Likely — 4 in 6        | Yes            | Restore           | Powerful          | Shelter           | Silence            | Rumor              | High, more than expected | Tyv          | spire        | Skies           | Sanctified      | Shadowy             | Spies               | Scorpion     | Tiara         | Tentacle     | River         | Shadowy               | Swamp                 | Thundering             | Springs                | Solitary            | Storm               | Stolen                 | Totem                  | Rain               | Wind               | West               | Evening            | Sealing          | Rough, stone-like surface  | Reveal           | Time             | Sound distortion    | Strength         | Sea Urchin      | Thought         | Tarot           | Very hard         | Repair            | Persevere        | Strength         | Spicy whiff      | Small creatures   | Somber mourning         | The quality of materials in the surroundings          | Someone's failure or refusal complicates your plans  | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Resist          | System          | Twisted            | Scientist          | Strong surveillance    | Secret code           | Lost relative found       | Title        | Secret identity           | Revelation     | Spike         | Revolution    | Spices           | Secluded              | Subterranean          | Rebellion stirs           | Security            | Secluded            | Sovereign judge       | Stoic indifference    | Uncharted land      | Secrets        | Resources       | Uri           | vel           | ot            | Respectful           | Searching            | Secretive     | Scout         | Scarred           | Silvered hair       | Salvation      | Sacrifice      | Stolen identity       | Shelter       | Strength      | Vex             | thos            | Towering        | Spider          | Sonic boom       | Sticky mucus           | Slash             | Surprise          |
| 31  | 6.1      | 3       | 7        | Likely — 4 in 6        | Yes            | Risk              | Radiant           | Superstition      | Sound              | Strategy           | High, more than expected | Uvan         | stone        | Space           | Suppressed      | Spectral            | Survivors           | Seaweed      | Tombstone     | Throne       | Spider Web    | Shattered             | Thicket               | Towering               | Statue                 | Terrifying          | Temple              | Strange                | Tracks                 | Rain               | Wind               | West               | Evening            | Shock            | Rustic, handcrafted look   | Reverse          | Vines            | Stars fading        | Sword            | Spider          | Time            | Torch           | Very hard         | Research          | Probe            | Subtlety         | Sweet honey      | Splashing waves   | Stealthy burglary       | The reverberation of sounds in the environment        | Someone's past actions come back to aid you          | Break (tool, limb, bond, trust, flow, promise)                    | Enhance (ability, sense, mood, credibility, result, intuition)    | Reveal          | Technology      | Tyrannical         | Secret Society     | Third party interested | Secret passage        | Prophecy about you        | Treasure     | Shift in allegiance       | Rift           | Spiral        | Sacred grove  | Spirituality     | Serene                | Towering              | Skeleton in every closet  | Spirituality        | Serene              | Street gang leader    | Subdued excitement    | Unclaimed throne    | Stability      | Sanctuaries     | Val           | ven           | oth           | Suspicious           | Sprinting            | Skilled       | Shaman        | Scheming          | Threadbare cloak    | Supremacy      | Shame          | Uncontrolled power    | Sponsorship   | Support       | Vor             | ulex            | Hulking         | Squid           | Soul drain       | Suction cups           | Snap              | Technology        |
| 32  | 6.2      | 4       | 8        | Very likely — 5 in 6   | Strong Yes     | Scheme            | Rustic            | Technology        | Space              | Structure          | Very high, the maximum   | Vorn         | theon        | Sword           | Traces          | Timeless            | Thieves             | Serpent      | Trident       | Undead       | Staircase     | Shifting              | Tundra                | Tranquil               | Stones                 | Threatening         | Tower               | Toxic                  | Trap                   | Rain               | Wind               | West               | Late night         | Storage          | Sleek, aerodynamic profile | Shape            | Void             | Stone skin          | Tsunami          | Telescope       | Time Loop       | Triquetra       | Very hard         | Retrieval         | Protect          | Technique        | Sweet-sour       | Sudden crack      | Tavern brawl            | The rhythm or pace of actions and movements           | Someone's success or cooperation opens new paths     | Harm (reputation, body, relationship, morale, perception, memory) | Reveal (clue, path, truth, alibi, pattern, source)                | Save            | Territory       | Undecipherable     | Sorcerer           | Time-sensitive         | Special training      | Old debt due              | Truce        | True lineage revealed     | Setback        | Stabilize     | Sanctuary     | Subsistence      | Shrouded              | Unkempt               | Supremacy struggle        | Storage             | Sparse              | Technocratic assembly | Sudden unease         | Underground passage | Technology     | Secrets         | Vyr           | wil           | uel           | Sympathetic          | Studying             | Tired         | Soldier       | Scrawny           | Unkempt beard       | Transcendence  | Sorrow         | Undercover spy        | Supplies      | Surveillance  | Vorak           | ulon            | Huge            | Stone           | Spawn minions    | Symbiotic organisms    | Strike            | Tenacity          |
| 33  | 6.3      | 1       | 9        | Very likely — 5 in 6   | Strong Yes     | Seek              | Severe            | Trust             | Spirit             | Threat             | Very high, the maximum   | Wyst         | tide         | Void            | Unknown         | Uncharted           | Vampires            | Stones       | Waves         | Whale        | Sundial       | Sinking               | Valley                | Twisted                | Trees                  | Vengeful            | Undead              | Trapped                | Vision                 | Rain               | Wind               | Northwest          | Late night         | Study            | Soft, velvety covering     | Summon           | Water            | Tech malfunction    | Veil             | Tornado         | Trap            | Virus           | Extreme           | Riddle            | Retreat          | Understanding    | Toasted aroma    | Ticking clock     | Tense interrogation     | The state of the sky and clouds                       | You are forced to reconsider your path               | Lose (evidence, way, ally, time, witness, balance)                | Save (time, ally, resource, reputation, momentum, memory)         | Spy on          | Tradition       | Unseen             | Swarm              | Transport issues       | Strategic outpost     | Enemy returns             | Vision       | True motive revelation    | Stagnation     | Subside       | Siege         | Trading post     | Stagnant              | Verdant               | Tragic defense failure    | Strategy            | Sprawling           | Thieves' syndicate    | Suspicious scrutiny   | Unmarked grave      | Texts          | Solace          | Wyn           | xis           | um            | Timid                | Surveying            | Wealthy       | Storyteller   | Stubborn          | Vivid tattoos       | Truth          | Survival       | Undisclosed illness   | Training      | Tools         | Vorm            | urn             | Enormous        | Swarm           | Telekinesis      | Telescopic limbs       | Stun              | Terrain           |
| 34  | 6.4      | 2       | 10       | Very likely — 5 in 6   | Strong Yes     | Soothe            | Solemn            | Vow               | Time               | Travel             | Very high, the maximum   | Xyr          | vale         | War             | Unregulated     | Untamed             | Witches             | Stump        | Wheel         | Witch Hat    | Unicorn       | Sparse                | Volcano               | Veiled                 | Vines                  | Violent             | Village             | Undiscovered           | Warning                | Thunderstorm       | Hurricane          | Northwest          | Late night         | Transportation   | Stark, contrasting lines   | Transfer         | Wave             | Time distortion     | Wall             | Tower           | Triskele        | Volcano         | Extreme           | Task              | Separate         | Weakness         | Vinegary odor    | Warning cry       | Thorough search         | The taste or sensation of something                   | You find a new lead on an existing quest             | Escalate (tension, stakes, threat, emotion, suspicion, noise)     | Obtain (evidence, ally, clearance, perspective, item, secret)     | Steal           | Treasure        | Unstable           | Undead             | Unknown technology     | Supernatural ally     | Events connected          | Wealth       | Trusted ally's betrayal   | Turning point  | Surge         | Summit        | Vineyard         | Thriving              | Vibrant               | Treacherous pact          | Trade               | Towering            | Trade consortium      | Unsettling silence    | Unseen predator     | Training       | Stories         | Xan           | yl            | ur            | Uninterested         | Training             | Wise          | Thief         | Taciturn          | Weathered skin      | Unity          | Thrill         | Unfulfilled promise   | Trust         | Transport     | Vraith          | uron            | Massive         | Specter         | Time warp        | Transparent shell      | Tear              | Trickery          |
| 35  | 6.5      | 3       | 11       | Very likely — 5 in 6   | Strong Yes     | Surrender         | Strong            | Voyage            | Water              | Truth              | Very high, the maximum   | Ysol         | wyn          | Wild            | Unstable        | Wandering           | Wizards             | Temple       | Windmill      | Worm         | Well          | Still                 | Wasteland             | Vibrant                | Wall                   | Weak                | Wanderer            | Unnatural              | Weapons                | Thunderstorm       | Hurricane          | Northwest          | Late night         | Warning          | Vibrant, shifting hues     | Transform        | Wind             | Uncontrollable rage | Wand             | Turtle          | Vase            | Whip            | Extreme           | Threat            | Stun             | Weapon           | Wet leaves       | Water drip        | Vigilant patrol         | The temperature of the air or surfaces                | Your progress is thwarted by an unforeseen obstacle  | Drain (energy, resources, hope, patience, focus, atmosphere)      | Exploit (weakness, loophole, distraction, emotion, pattern, info) | Strengthen      | Vision          | Vengeful           | Warlord            | Unstable environment   | Underground network   | Trap or ambush            | Weapon       | Unexpected inheritance    | Veering        | Tighten       | Treaty        | Wisdom           | Uncharted             | Wide                  | Tyranny's shadow          | Training            | Verdant             | Warrior chieftain     | Vibrant energy        | Vanishing villagers | Warriors       | Traditions      | Zan           | yon           | us            | Warm                 | Working              | Wounded       | Tinkerer      | Unassuming        | Whistling habit     | Wealth         | Tradition      | Unnatural talent      | Understanding | Weapons       | Zen             | ythr            | Gargantuan      | Undead          | Toxic spores     | Vaporous exhale        | Thrash            | Violence          |
| 36  | 6.6      | 4       | 12       | Very likely — 5 in 6   | Strong Yes     | Traverse          | Wise              | Wisdom            | Weakness           | Wealth             | Very high, the maximum   | Zan          | yarn         | Wood            | Widespread      | War-torn            | Zombies             | Werewolf     | Wizard        | Ziggurat     | Wooden Shield | Wicked                | Woods                 | Weathered              | Waterfall              | Wild                | Wildfire            | Valuable               | Wreckage               | Thunderstorm       | Hurricane          | Northwest          | Late night         | Worship          | Weathered appearance       | Warp             | Wood             | Weather anomalies   | Water-Resistant  | Vial            | Void            | Wing            | Extreme           | Trap              | Surprise         | Wound            | Zesty fragrance  | Whispers          | Village assembly        | The way light filters into the scene                  | Your talents gain unexpected recognition             | Expose (secret, lie, agenda, weakness, location, intention)       | Prevent (harm, exposure, loss, conflict, deception, escalation)   | Survive         | Weapon          | Voracious          | Zealot             | Weather hazards        | Wise sage             | Power surge               | Wisdom       | Villain's true identity   | Wrong turn     | Wane          | Witch trials  | Workshop         | Wild                  | Withered              | Vital passage blocked     | Worship             | Weathered           | Witch coven           | Welcoming warmth      | Wandering specter   | Wisdom         | Treasures       | Zor           | zar           | yn            | Wary                 | Writing              | Young         | Trader        | Vigilant          | Wistful glance      | Wisdom         | Vengeance      | Unsolved crime        | Work          | Wisdom        | Zoth            | yx              | Colossal        | Worm            | Weather control  | Venomous thorns        | Trample           | Weapons           |
^data
