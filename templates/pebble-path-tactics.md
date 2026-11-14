# Pebble Path Tactics

*Plan every step, then watch your hedgehog trot home*

**Category:** Games · **Ages:** Ages 6–10 · **Chinese name:** 鹅卵石小路战术 · **Spec version:** 1.0

## What it is

A gentle turn-based tactics game on a garden grid. Players lay down move cards first — up, down, left, right — planning the whole route before anything moves, then press Go and watch their hedgehog follow the plan exactly. Puddles block a square, stars are collected by stepping on them, and the flag is home. Because the whole plan is made before the run, a wrong turn is never a punishment: rewind, swap one card, and try again. Short levels teach sequencing, spatial reasoning and calm debugging.

## Features

- Plan-then-run move cards — no fast reflexes, no timers
- 12 hand-built garden levels from 4×4 to 6×6
- Puddles, stars and a home flag on every level
- Rewind-and-edit debugging with no fail state
- Solo and cooperative two-player planning
- Parent note on sequencing and spatial skills

## What's included

- 12 garden levels from 4×4 to 6×6
- Plan-then-run move cards & rewind editor
- Solo & co-op two-player planning
- Parent note on sequencing & spatial skills

## At a glance

- Plan first, move second — lay every move card before the hedgehog takes a single step
- Puddles block, stars collect, the gold flag is home — every level is solvable by design
- No timers, no fail state — rewind, swap one card, and run your plan again

## How it works

1. Look at the grid and where the stars and puddles are
2. Lay move cards in order to build a full plan
3. Press Go — the hedgehog follows the cards exactly
4. Collect all stars and finish on the flag; if a card bumps a puddle, rewind, edit that one card, and run again

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The hedgehog's planner is cheered on by this name
  - Default: Alex
- **Age band** (single) — Level size and reading load tune to the age band
  - Choices: Ages 5–6 / Ages 6–7 / Ages 7–8 / Ages 9–10
  - Default: Ages 7–8
- **Board size** (single) — Starter boards are 4×4, classic 5×5, explorer 6×6
  - Choices: 4 × 4 (starter) / 5 × 5 (classic) / 6 × 6 (explorer)
  - Default: 5 × 5 (classic)
- **Garden theme** (single) — The world each level's grid is dressed as
  - Choices: Meadow & puddles / Harbour & barrels / Snowfield & ice patches / Night garden & lanterns
  - Default: Meadow & puddles
- **Difficulty** (single) — How twisty the routes and puddle layouts get
  - Choices: Gentle / Steady / Challenge
  - Default: Steady
- **Session length** (single) — Levels are sized to fit the session
  - Choices: About 10 min / About 15 min / About 20 min / About 30 min
  - Default: About 15 min
- **Game language** (single) — The language the game speaks and prints
  - Choices: English / Chinese (中文) / Spanish (Español) / Japanese (日本語) / Korean (한국어)
  - Default: English
- **Play mode** (single) — Who lays the move cards
  - Choices: Solo planning / Co-op — plan together / Take turns planning
  - Default: Solo planning
- **Hints** (single) — How much help appears when a plan bumps a puddle
  - Choices: Show a ghost step / Verbal hint only / No hints
  - Default: Show a ghost step

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a younger player, ages 5–6, smallest board, gentle difficulty and short sessions
- Harbour theme, explorer board, challenge difficulty, about 30 minutes, co-op play
- Night garden theme in Chinese, steady difficulty, verbal hints only

## Sample content

### Sample Level · Level 3: Two Stars by the Puddle (complete solved level)

LEVEL 3: TWO STARS BY THE PUDDLE — a complete solved level.

THE GRID: 5 columns (A–E, left to right) by 5 rows (1–5, top to bottom). Start: the hedgehog at A5 (bottom-left). Flag (home): E1 (top-right). Stars: at C4 and D2. Puddles (blocked — the hedgehog cannot enter them): B4, C3 and E3. Every other square is open grass.

THE VERIFIED WINNING PLAN — exactly 8 move cards: Right, Right, Up, Right, Up, Up, Right, Up.

STEP BY STEP (check each square as the hedgehog trots):
1. Right — A5 → B5. Open grass.
2. Right — B5 → C5. Open grass.
3. Up — C5 → C4. Collect Star 1.
4. Right — C4 → D4. Open grass.
5. Up — D4 → D3. Open grass.
6. Up — D3 → D2. Collect Star 2.
7. Right — D2 → E2. Open grass.
8. Up — E2 → E1. The flag — home!
No step enters B4, C3 or E3, so no card ever bumps a puddle.

WHY THE TEMPTING SHORTER TRY FAILS: from C4 (just after collecting Star 1) it is tempting to go straight Up toward the flag — but C3 is a puddle, and a puddle square cannot be entered. The plan bounces there. That is exactly why the winning plan detours Right to D4 first, then climbs the clear D column to Star 2 at D2. One swapped card fixes the whole route — that is the debugging move this game teaches.

SCORING: stars collected are shown as 2/2. There is no speed bonus and no timer. Rewinds are unlimited and free — rewind, swap one card, and run the plan again as many times as you like.

TRY IT YOURSELF (stated, not solved — find the route!): a 4×4 grid. Start at A4. Flag at D1. Stars at B3 and C2. Puddles at B2 and D3. Hint: you will need exactly 6 moves if your route visits both stars. Lay your cards, press Go, and see.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
