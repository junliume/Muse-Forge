# The Hundred Chart Workshop

*Find the pattern hiding in the hundred chart*

**Category:** Education · **Ages:** Ages 6–8 · **Chinese name:** 百格图工坊 · **Spec version:** 1.0

## What it is

A hands-on number-pattern workshop built around the hundred chart (1–100 in ten rows). Learners hunt for missing numbers, follow jumps of +1, +10 and −10, spot odd/even and diagonal patterns, and explain how they know — one small detective step at a time. Every puzzle is worked end-to-end in the sample, so children check their reasoning, not just their answer. No timers, no ranking, no speed rewards.

## Features

- Missing-number hunts with worked reasoning
- Jumps of +1, +10 and −10 made visible on the grid
- Odd/even, row and diagonal pattern spotting
- Explain-how-you-know prompts after each puzzle
- Parent view: patterns mastered + puzzles to revisit

## What's included

- Hundred chart board (1–100)
- Pattern puzzle deck
- Worked reasoning cards
- Parent progress view

## At a glance

- A 10×10 hundred chart with three tiles flipped over — find the missing numbers from their neighbours
- Follow the +10 ladder straight down a column and say why every stop ends in the same digit
- Shade the diagonal and spot the pattern: 11, 22, 33 — each step adds 11

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Learner's name** (text) — The workshop will greet the learner by this name
  - Default: Alex
- **Grade** (single)
  - Choices: Grade 1 / Grade 2 / Grade 3
  - Default: Grade 2
- **Chart skills to practise** (multi)
  - Choices: Missing numbers / The +10 ladder / Odd & even patterns / Diagonals (+11)
  - Default: Missing numbers, The +10 ladder
- **Practice language** (single)
  - Choices: English / English + Chinese help / Chinese (中文)
  - Default: English
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Puzzles per session** (single)
  - Choices: 4 puzzles / 6 puzzles / 8 puzzles
  - Default: 6 puzzles
- **Hint style** (single)
  - Choices: Show the move first / Ask a guiding question / Let me try twice first
  - Default: Ask a guiding question
- **Explain-how-you-know** (single)
  - Choices: Say it out loud / Pick the reason / Write a short sentence
  - Default: Say it out loud
- **Parent view** (single)
  - Choices: Patterns mastered + revisit list / Session summary only / Off
  - Default: Patterns mastered + revisit list

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a Grade 1 learner, missing numbers only, 4 puzzles, about 10 minutes, show the move first
- Grade 3, add diagonals and odd & even patterns, 8 puzzles, let me try twice first
- Bilingual practice in English with Chinese help, 6 puzzles, explain by picking the reason

## Sample content

### Sample Lesson · The Covered Tiles: Missing Numbers & the +10 Ladder (complete worked lesson)

THE BOARD: The hundred chart has 10 rows. Row 1 is 1–10, row 2 is 11–20, and so on to 91–100. Moving RIGHT adds 1. Moving DOWN adds 10. That is the whole secret — every puzzle below uses only those two moves.

PUZZLE 1 — THE COVERED TILES: Three tiles are covered. Tile A sits between 34 and 36, so A = 35 (right adds 1: 34, 35, 36 ✓). Tile B sits directly below 27, so B = 27 + 10 = 37 ✓. Tile C sits directly above 82, so C = 82 − 10 = 72 ✓. Explain-how-you-know: 'B is below 27, and down means +10.'

PUZZLE 2 — THE +10 LADDER: Start at 14. Go down one row: 24. Down again: 34, 44, 54. Every stop ends in 4, because adding 10 changes only the tens digit — the ones digit never moves. Check: 14 + 10 + 10 + 10 + 10 = 54 ✓.

PUZZLE 3 — THE DIAGONAL: Start at 11, move down-right: 22, 33, 44. Each diagonal step is +11 (down +10, right +1). 11 + 11 = 22 ✓, 22 + 11 = 33 ✓. The tens and ones digits both grow by 1, which is why the numbers look like twins.

PUZZLE 4 — ODD OR EVEN? 47 is odd (ends in 7). The number below it, 57, is also odd — adding 10 never changes odd/even, because 10 is even. The number to its right, 48, is even — adding 1 flips odd to even. ✓

FINISH & CHECK: Cover 63. What is above it? 53 (63 − 10). Below it? 73 (63 + 10). Left? 62. Right? 64. All four answers use only +1 / −1 / +10 / −10 — if an answer needs any other jump, look again.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
