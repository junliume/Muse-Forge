# Compass Rose Quest

*Navigate by clues, not by guessing — a map-logic adventure*

**Category:** Games · **Also listed under:** Education · **Ages:** Ages 7–11 · **Chinese name:** 罗盘玫瑰大冒险 · **Spec version:** 1.0

## What it is

A calm map-logic adventure where every move is earned by a clue. Players read a short compass clue, find the one route it allows, and step — no guessing, no timers, no failing. Each island is a small verified logic puzzle: three signposts, one true route, and a friendly keeper who explains WHY the other routes cannot be right. Wrong taps are explained from the clue, never punished, and the player tries again. Finishing an island unlocks its stamp and a harder clue type: first single clues, then two clues that must BOTH hold, then clues about what is NOT true.

## Features

- Every puzzle verified to have exactly one solution
- No timers, no scores, no fail state — clues are re-read and retried
- Clue types grow: single, paired, and NOT clues
- Keeper explains why each wrong route breaks the clue

## What's included

- 6-island clue voyage
- Verified clue-logic engine (every puzzle has exactly one solution)
- Keeper explanations for every wrong route
- Island stamp collection
- Parent voyage log

## At a glance

- Read the clue, find the ONE route it allows — every island has exactly one solution
- The keeper explains why each wrong route breaks the clue — no guessing, no punishment
- Collect an island stamp for each voyage finished, then face a harder clue type

## How it works

1. Read the compass clue aloud with Keeper Wren and look at the three signposts
2. Work the clue part by part — cross out every route it rules out until exactly one route survives
3. Step onto the true route, collect the island stamp, and sail on to a harder clue type

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The keeper will call the player by this name
  - Default: Alex
- **Age band** (single)
  - Choices: Ages 6–7 / Ages 7–9 / Ages 9–11
  - Default: Ages 7–9
- **Clue difficulty** (single)
  - Choices: Single clues only / Single + paired clues / All clue types incl. NOT clues
  - Default: Single + paired clues
- **Play language** (single)
  - Choices: English / Chinese (中文) / Spanish (Español) / Japanese (日本語) / Korean (한국어)
  - Default: English
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 25 min
  - Default: About 15 min
- **Hint style** (single)
  - Choices: Keeper explains first / Try twice, then keeper explains / Hints only when asked
  - Default: Keeper explains first
- **Island themes** (multi)
  - Choices: Lighthouses & harbours / Pine woods & mills / Rocky coves / Sandy spits
  - Default: Lighthouses & harbours, Pine woods & mills

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a 7-year-old, single clues only, about 10 minutes, keeper explains first
- Harder please: all clue types including NOT clues, hints only when asked, about 25 minutes
- In Chinese, with lighthouse and rocky cove islands, about 15 minutes

## Sample content

### Sample Island 1 · Bramble Cay: The Three Signposts (complete worked island)

THE CLUE (read aloud by Keeper Wren): “The true route is NOT the north route, and it passes a lighthouse.” THE THREE SIGNPOSTS: North route — passes a lighthouse and a pine wood. East route — passes a lighthouse and a millpond. West route — passes a pine wood only. SOLVE IT STEP BY STEP: Step 1 — Use the NOT part first. The clue says the true route is NOT north, so cross out the North route, even though it does pass a lighthouse. Step 2 — Use the lighthouse part. Of the routes left (East and West), only East passes a lighthouse; West passes only a pine wood, so West cannot be right. Step 3 — Check the survivor against BOTH parts: East is not north ✓ and East passes a lighthouse ✓. ANSWER: The East route — and it is the ONLY route that fits both parts, which is why this island always works. KEEPER LINES FOR WRONG TAPS: If you tap North: “North does pass a lighthouse — good spotting! But the clue also said NOT north, so North breaks the first part.” If you tap West: “West is not north — that part fits! But West never passes a lighthouse, so it breaks the second part.” ISLAND 1 STAMP: The Lighthouse Stamp. NEXT ISLAND PREVIEW: Island 2, Gull Rock, uses two clues that must BOTH hold at once.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
