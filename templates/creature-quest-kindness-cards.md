# Creature Quest: Kindness Card Puzzles

*Combine creature cards, solve the puzzle guardians, win with clever kindness.*

**Category:** Games · **Ages:** Ages 8+ · **Chinese name:** 小怪兽善意卡牌 · **Spec version:** 1.0

## What it is

Deck-combination puzzles where you befriend guardians instead of fighting them. Each guardian shows Kindness Slots — a sequence of types to fill in order. Play cards matching the slot types; wrong cards cost 0 Spark and come back with a picture hint. You carry 6 Spark per guardian, refilled at every rest. Most guardians have two or more valid solutions, and every card unlocks in a fixed order — no packs, no luck, just thinking.

## Features

- Kindness Slots: fill the type sequence in order
- Wrong cards cost 0 Spark and return with a picture hint
- Most guardians have 2+ valid solutions
- All cards unlock in fixed order — no packs, no luck
- Parent Zone shows both solutions per guardian

## What's included

- Trail puzzle packs
- Creature card deck
- Chain Star system
- Parent Zone with solutions

## At a glance

- Fill each guardian's Kindness Slots in order to befriend them
- Wrong cards cost nothing and come back with a picture hint
- Most guardians have two or more valid solutions

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Your version's name** (text)
  - Default: My Creature Quest
- **World theme** (single)
  - Choices: Bramblewood / Coral Coast / Cloud Highlands
  - Default: Bramblewood
- **Trails** (single)
  - Choices: 3 trails / 5 trails / 8 trails
  - Default: 5 trails
- **Guardians per trail** (single)
  - Choices: 3 guardians / 5 guardians / 7 guardians
  - Default: 5 guardians
- **Kindness Slots per guardian** (single)
  - Choices: 2 slots / 3 slots / 4 slots
  - Default: 3 slots
- **Difficulty** (single)
  - Choices: Picture clues / Picture + word / Riddle mode
  - Default: Picture + word
- **Player mode** (single)
  - Choices: Solo / 2-player co-op hand
  - Default: Solo
- **Language** (single)
  - Choices: English / Chinese (中文)
  - Default: English

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Coral Coast world, riddle mode, 4 slots per guardian
- Picture clues only, 3 guardians per trail, for a younger player
- 2-player co-op hand in the Cloud Highlands

## Sample content

### Trail 1 · Quest 1: Bramble Bear (two full solutions)

Bramble Bear is tangled, grumbly, and stuck. His Kindness Slots read: Soften → Grow → Warm. Your fixed 5-card hand: Rain Mouse (Water 1), Song Finch (Music 2), Sprout Pup (Plant 1), Sun Chick (Sun 2), Cozy Cat (Cozy 1). Solution A — Rain Mouse (Water softens the brambles, 1 Spark) → Sprout Pup (Plant grows through; the Rain→Plant Chain Star makes this pair sing, 1 Spark) → Sun Chick (Sun warms him dry, 2 Spark). Total 4 of 6 Spark — bear befriended, one star for the chain. Solution B — Song Finch (Music softens his mood, 2) → Sun Chick (Warm, 2) → Cozy Cat (Cozy finishes the Grow slot as a comfort-grow, 1). Total 5 of 6 — also correct. The scripted wrong-try moment: play Cozy Cat first and Bear shakes his head — the card returns, costs nothing, and a picture hint shows rain on brambles: “Softening comes first. What makes hard things soft?”

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
