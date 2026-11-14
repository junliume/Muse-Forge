# The Clockwork Caravan

*A cooperative route-and-order puzzle adventure*

**Category:** Games · **Ages:** Ages 7–10 · **Chinese name:** 发条商队 · **Spec version:** 1.0

## What it is

A cooperative puzzle adventure about a little clockwork caravan that only moves when the whole route is planned first. Players read the clues, order the carts, balance the loads and crack the gear codes before anyone turns the key — then watch the caravan roll through the gates exactly as planned. Every level is solvable from its clues alone, there are no timers and no fail state: a wrong plan just winds back, one clue is re-read, and the caravan tries again. Short levels teach sequencing, deduction, balancing and pattern-spotting, solo or together.

## Features

- Plan the whole route first — no timers, no reflexes, no fail state
- Three gate types in every level: order, balance and gear-code puzzles
- Every puzzle is solvable from its clues alone, with a worked solution
- Tiered hints that re-read one clue instead of giving the answer away
- Solo, co-op and take-turns planning modes

## What's included

- 12 caravan levels across 4 themed roads
- Order, balance & gear-code gate puzzles with worked solutions
- Tiered hint cards & wind-back retry
- Solo, co-op & take-turns planning modes
- Parent note on deduction & sequencing skills

## At a glance

- Three gates, three clue types — order the carts, balance the crates, crack the repeating gear code
- Plan everything before the key turns: the caravan only ever does exactly what you planned
- No timers, no fail state — wind back, re-read one clue, change one thing, roll again

## How it works

1. Read the level's three gate clues out loud together
2. Plan the cart order, the balanced loads and the gear code before turning the key
3. Turn the key — the caravan rolls exactly as planned
4. If a gate stays shut, wind back, re-read one clue, change one thing and roll again

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The caravan's planner is cheered on by this name
  - Default: Alex
- **Age band** (single) — Clue reading load and puzzle size tune to the age band
  - Choices: Ages 5–6 / Ages 6–7 / Ages 7–8 / Ages 9–10
  - Default: Ages 7–8
- **Game language** (single) — The language the game speaks and prints
  - Choices: English / Chinese (中文) / Spanish (Español) / Japanese (日本語) / Korean (한국어)
  - Default: English
- **Session length** (single) — Levels are sized to fit the session
  - Choices: About 10 min / About 15 min / About 20 min / About 30 min
  - Default: About 15 min
- **Play mode** (single) — Who reads the clues and turns the key
  - Choices: Solo planning / Co-op — plan together / Take turns planning
  - Default: Solo planning
- **Difficulty** (single) — How many clues each gate needs and how twisty they get
  - Choices: Gentle / Steady / Challenge
  - Default: Steady
- **Puzzle focus** (multi) — Levels lean toward the gate types you pick
  - Choices: Order & sequence / Routes & maps / Balancing loads / Codes & patterns
  - Default: Order & sequence, Routes & maps
- **Hints** (single) — How much help appears when a gate stays shut
  - Choices: Show a worked clue / Verbal hint only / No hints
  - Default: Show a worked clue
- **Caravan theme** (single) — The world the caravan's roads run through
  - Choices: Meadow roads & windmills / Desert wells & dunes / Snow passes & pine forests / Harbour roads & lanterns
  - Default: Meadow roads & windmills

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a younger player, ages 5–6, gentle difficulty and short 10-minute co-op sessions
- Desert wells theme, challenge difficulty, about 30 minutes, focus on codes and patterns only
- Harbour roads theme in Chinese, steady difficulty, verbal hints only, take turns planning

## Sample content

### Sample · Level 1: The Three Gates of Willow Ford (complete solved level)

LEVEL 1: THE THREE GATES OF WILLOW FORD — a complete solved level. The caravan has three carts: the Bell cart, the Lantern cart and the Sprocket cart. Plan all three gates first, then turn the key.

GATE 1 — THE ORDER GATE (a narrow bridge, one cart at a time). Clues: (1) The Bell cart must cross before the Lantern cart. (2) The Sprocket cart is not first. (3) The Lantern cart is not last. WORKED SOLUTION: The Lantern cart is not last, so it is first or second. It cannot be first, because the Bell cart must cross before it — so the Lantern cart is second and the Bell cart is first. The Sprocket cart takes the last place, which fits clue (2). ORDER: 1. Bell, 2. Lantern, 3. Sprocket. No other order fits all three clues.

GATE 2 — THE BALANCE GATE (a beam scale that only lifts when both pans are equal). Four crates weigh 2, 3, 4 and 5 stones. Put two crates on each pan so the pans balance. WORKED SOLUTION: 2 + 5 = 7 and 3 + 4 = 7 — the pans balance at 7 stones each. CHECK THE OTHER PAIRINGS: 2 + 3 = 5 against 4 + 5 = 9 (no), and 2 + 4 = 6 against 3 + 5 = 8 (no), so this is the only pairing that works.

GATE 3 — THE GEAR-CODE GATE (a dial that repeats its pattern). The dials already showing read: 3, 1, 4, 3, 1, and one dial is still blank. WORKED SOLUTION: The pattern is 3, 1, 4 repeating — after 3, 1, 4 the dials start again with 3, 1, so the blank dial is 4. Set the blank dial to 4 and the gate clicks open.

TURN THE KEY: Bell, Lantern, Sprocket roll over the bridge in order; the balanced beam lifts; the gear dial set to 4 unlocks the last gate — and the caravan winds its way into Willow Ford for tea. If any gate had stayed shut, the caravan would simply wind back: re-read one clue, change one thing, and roll again. There is never a fail state.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
