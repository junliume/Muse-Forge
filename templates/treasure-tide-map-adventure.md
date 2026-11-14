# Treasure Tide: Map Adventure

*Plan the route, ride the tides, find the treasure — together.*

**Category:** Games · **Ages:** Ages 6+ · **Chinese name:** 潮汐宝藏地图 · **Spec version:** 1.0

## What it is

A family co-op board adventure on a living map. Each round a Tide Card changes the map — bridges flood, ferries move, pools block the path — and the crew re-plans together. Collect 3 Map Fragments and reach the Lighthouse. When the Moon Track fills, the tide simply resets: fragments are KEPT, nobody loses, and there is never a game over — just a new map to think about.

## Features

- Tide Card changes the map every round
- Collect 3 Map Fragments, reach the Lighthouse — together
- Moon Track full = tide resets, fragments kept, never game over
- 1–4 player family co-op on one shared map
- Per-island reset + route-planning practice puzzles

## What's included

- Island map packs
- Tide Card deck
- Practice route puzzles
- Parent Zone

## At a glance

- A Tide Card changes the map every round — re-plan together
- Collect 3 Map Fragments and reach the Lighthouse
- The tide can reset the map, but fragments are kept — never game over

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Your version's name** (text)
  - Default: My Treasure Tide
- **Map theme** (single)
  - Choices: Three Bays Islands / River Delta / Snowy Fjords / Desert Oasis
  - Default: Three Bays Islands
- **Map size** (single)
  - Choices: 5×5 / 6×6 / 7×7 / 8×8
  - Default: 6×6
- **Map fragments to collect** (single)
  - Choices: 2 fragments / 3 fragments / 4 fragments
  - Default: 3 fragments
- **Players** (single)
  - Choices: 1 player / 2 players / 3 players / 4 players
  - Default: 2 players
- **Tide complexity** (single)
  - Choices: Gentle tides / Standard tides / Tricky tides
  - Default: Standard tides
- **Islands** (single)
  - Choices: 3 islands / 5 islands / 8 islands
  - Default: 5 islands
- **Language** (single)
  - Choices: English / Chinese (中文)
  - Default: English

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Snowy Fjords map, 7×7, for 4 players with tricky tides
- Gentle tides and 2 fragments for a first game with a 6-year-old
- River Delta, 8 islands, standard tides

## Sample content

### Island 1 · Three Bays Island (5-round worked playthrough)

The 6×6 board: Camp at A1, Lighthouse at F6. Fragments wait at C2, B5, and E4. The North Bridge (D5–E5) floods on High Tide; the South Ferry sails A3 ↔ F3; the Crab Pools (C4, E2) are always blocked. Round 1 (Low Tide): cross to C2, take Fragment 1. Round 2 (Rising): head south before the bridge floods; the ferry carries the crew A3 → F3. Round 3 (High Tide): the bridge is under water — good thing the plan went south; climb to E4, Fragment 2. Round 4 (Falling): pools still block the middle, so swing wide through B5, Fragment 3. Round 5 (Low Tide): the bridge is back — D5–E5, then F6: the Lighthouse, together. Practice puzzle, Shortest Safe Route: from Camp, on High Tide, reach B5 without crossing the flooded bridge or stepping in the pools — solution: A1 → A2 → A3, ferry to F3, then F4 → E4 → D4 → D5 (stand on the bridge's near end, don't cross) → C5 → B5. The trick: the flood closes the crossing, not the square — read the map, not your assumptions.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
