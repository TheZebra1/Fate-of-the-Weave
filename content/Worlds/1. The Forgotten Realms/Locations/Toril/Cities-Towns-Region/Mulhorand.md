---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Small City
Alignment: Lawful Neutral
Government: Theocracy
type: Settlement
politics: Lordship
leader: The Pharaoh
guildsgroups:
  - The Priesthood of the Gods
  - The Enforcers of Divine Will
  - Artisan Guild
region:
  - Eastern Shaar
  - Untheric Border
size: Metropolis
population: 120,000
commonraces:
  - Humans
  - Aasimar
  - Genasi
religion:
  - Horus-Re
  - Isis
  - Osiris
  - Set
exports:
  - Fine Spices
  - Jewelry
  - Religious Artifacts
imports:
  - Exotic Silks
  - Iron
---

> [!infobox]
> # `=this.file.name`
>![[Pasted image 20250110004023.webp]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ---|---|
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)

# `=this.file.name`
## Overview
Mulhorand is a grand theocratic city where divine law governs all aspects of life. The city is deeply influenced by its pantheon of gods, and temples dominate its skyline.

### Placeholder Picture
![[Mulhorand.webp|500]]
*An aerial view of Mulhorand showcasing its grand temples and bustling markets.*
## Notable NPCs
- The Pharaoh: Divine ruler and living avatar of Horus-Re.
- High Priestess Isis: Leader of the priesthood.
- Set's Chosen: A shadowy figure said to represent the god Set's influence.

## History
Mulhorand's history is steeped in divine intervention, with its pantheon of gods actively shaping its rise as a theocratic power.

## Points of Interest
- The Great Temple of Horus-Re
- The Eternal Obelisk
- The River of Life Market

## Internal Relationships
The priesthood wields tremendous power, but rivalries between the temples of Set and Horus-Re create tension.

## Outward Relationships
Mulhorand maintains a wary truce with nearby Unther while engaging in active trade with the Shaar.

## Background
Mulhorand is one of the most ancient and storied cities in Faerûn, blending powerful magic with divine authority to maintain its influence over the region.
