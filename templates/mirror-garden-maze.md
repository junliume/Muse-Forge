# The Mirror Garden Maze

*Bounce sunlight to the flowers with clever mirrors*

**Category:** Games · **Ages:** Ages 7–11 · **Chinese name:** 镜子花园迷宫 · **Spec version:** 1.0

## What it is

A gentle logic game about light and mirrors. A sunbeam enters a small garden grid heading in one direction. Players place diagonal mirrors to turn the beam — a / mirror turns an eastbound beam north and a northbound beam east; a \ mirror turns an eastbound beam south and a southbound beam east — and try to land the beam exactly on a sleepy flower so it blooms. Each level is a short chain: predict the path, place one or two mirrors, trace the beam step by step, then check. There are no timers, no points for speed, and no failing out — a beam that misses just fades at the garden wall and invites another try. Levels grow from one mirror on a 3 by 3 grid to two mirrors and a decoy flower on a 4 by 4 grid.

## Features

- Predict-then-place mirror logic with step-by-step beam tracing
- Verified solvable levels — every sample level is worked end-to-end
- No timers and no speed scores — misses are information not failure
- Garden artwork in the Games violet and green palette

## What's included

- 12 garden levels (3x3 to 4x4)
- Mirror rule card (/ and \ reflections)
- Beam-tracing checker
- Bloom journal

## At a glance

- Predict first — where will the beam go if this mirror turns it north?
- Place a / or \ mirror, then trace the beam square by square to the flower
- A missed beam fades at the wall — move one mirror and try again, no penalty

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The garden journal will use this name
  - Default: Alex
- **Age band** (single)
  - Choices: Ages 5-6 / Ages 7-8 / Ages 9-11 / Mixed ages
  - Default: Ages 7-8
- **Garden size** (single)
  - Choices: 3 by 3 only / 3 by 3 to 4 by 4 / Up to 5 by 5
  - Default: 3 by 3 to 4 by 4
- **Mirrors per level** (single)
  - Choices: One mirror / One to two mirrors / Up to three mirrors
  - Default: One to two mirrors
- **Skills to practice** (multi)
  - Choices: Predicting paths / Mirror rules / Step-by-step tracing / Planning two turns
  - Default: Predicting paths, Mirror rules
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Language** (single)
  - Choices: English / English + Chinese / Chinese (中文) / Spanish / Japanese / Korean
  - Default: English
- **Difficulty** (single)
  - Choices: Gentle / Steady / Challenge
  - Default: Steady
- **Play mode** (single)
  - Choices: Solo / Take turns with a partner / Predict together
  - Default: Solo

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- One mirror only on a 3 by 3 garden, gentlest difficulty, about 10 minutes, Ages 5-6
- Two mirrors and planning two turns for a challenge, about 20 minutes in English + Chinese
- Take turns with a partner, focus on step-by-step tracing only

## Sample content

### Sample Level · Level 1 — Wake the Sunflower (fully worked, verified)

RULE CARD: Beam headings are North, East, South, West. A / mirror: East→North, North→East, South→West, West→South. A \ mirror: East→South, South→East, North→West, West→North.

LEVEL 1 — grid 3 rows by 3 columns, rows counted top to bottom, columns left to right. The beam starts just left of square (2,1) heading East. There is one / mirror already placed at (2,2). The sunflower target is at (1,2).

WORKED SOLUTION, step by step: Step 1 — the beam enters (2,1) heading East and crosses it unchanged. Step 2 — the beam enters (2,2) heading East and hits the / mirror, so it turns North (East→North for /). Step 3 — the beam enters (1,2) heading North and lands exactly on the sunflower — the flower blooms. Level solved with the one mirror given.

CHECK THE MISS: if the mirror at (2,2) were \ instead, East would turn South to (3,2) and then out through the bottom wall — no bloom — so / is the only correct choice for this level.

LEVEL 2 PREVIEW (also verified): beam starts left of (3,1) heading East, / mirror at (3,3), path (3,1)→(3,2)→(3,3) turn North→(2,3)→(1,3) tulip blooms. Solved with one / mirror at (3,3).

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
