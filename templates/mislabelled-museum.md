# The Mislabelled Museum

*A cozy deduction game: read the clues, place every exhibit*

**Category:** Games · **Ages:** Ages 8–12 · **Chinese name:** 贴错标签的博物馆 · **Spec version:** 1.0

## What it is

Every morning the little museum opens to find its labels shuffled in the night. Four exhibits, four halls, and a handful of honest clues — your job is to read carefully, reason step by step, and place each exhibit where it truly belongs. There is exactly one solution to every case, and the game never rushes you: place everything first, check only when you are ready, and use gentle hints that point back at the clue you have not used yet. Cases grow from 3 halls to a grand 5-hall wing, and a Casebook keeps the cases you have solved. Original cases only, written for this template.

## Features

- One true solution per case — every case is logic-checked end to end
- Clues that reward careful reading, not guessing
- Place first, check when ready — no timers, no fail states
- Gentle hints that point to an unused clue, never the answer
- Casebook of solved cases with your reasoning streaks

## What's included

- Case library (40+ original cases)
- Clue-by-clue hint ladder
- Casebook & solution replays
- Parent case log

## At a glance

- Four exhibits, four halls, four honest clues — and exactly one solution
- Hints never give the answer: they point you back to the clue you have not used yet
- A Casebook keeps every solved case, so a favourite can be replayed any time

## How it works

1. Open a case and meet the exhibits and halls.
2. Read every clue — each one rules something in or out.
3. Drag or tap to place each exhibit in a hall.
4. Press Check when all are placed; if something is off, a hint points to the clue to re-read.

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — Placeholder only — a first name or nickname
  - Default: Alex
- **Age band** (single)
  - Choices: Ages 7–8 / Ages 9–10 / Ages 11–12
  - Default: Ages 9–10
- **Halls per case** (single)
  - Choices: 3 halls — quick case / 4 halls — classic case / 5 halls — grand case
  - Default: 4 halls — classic case
- **Museum wings** (multi)
  - Choices: Harbor museum / Space station / Garden library / Night market / Clock tower
  - Default: Harbor museum, Garden library
- **Clue style** (single)
  - Choices: Plain and direct / Story-flavoured / Extra tricky (one red-herring-free twist)
  - Default: Plain and direct
- **Hints** (single)
  - Choices: Gentle nudge to an unused clue / Hints off — pure deduction / Step-by-step reasoning coach
  - Default: Gentle nudge to an unused clue
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 25 min
  - Default: About 15 min
- **Game language** (single)
  - Choices: English / Chinese (中文) / Bilingual EN + 中文
  - Default: English

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Make it a grand 5-hall case in the space station wing, extra tricky clues, about 25 minutes
- Quick 3-hall cases for a 7-year-old, story-flavoured clues, with the step-by-step reasoning coach on
- Bilingual cases in the night market wing, hints off — pure deduction

## Sample content

### Sample Case 1 · The Four Halls (complete case with worked solution)

THE SET-UP: The museum has four halls — North, East, South, West — and four exhibits: the Brass Compass, the Jade Turtle, the Silver Kite, and the Painted Drum. Opposite pairs: North is opposite South, East is opposite West. Every exhibit goes in exactly one hall, and every hall holds exactly one exhibit.

THE CLUES:
(1) The Jade Turtle is in the East Hall or the South Hall.
(2) The Brass Compass is not in the North Hall or the East Hall.
(3) The Painted Drum is in the hall opposite the Brass Compass.
(4) The Silver Kite is not in the North Hall.

WORKED REASONING: From clue 2 the Compass is in the South or West Hall. Suppose the Compass were in the West Hall: then clue 3 puts the Drum in the East Hall (opposite West), clue 1 then forces the Turtle into the South Hall (East is taken), and the Kite would be left with the North Hall — but clue 4 forbids that. So the Compass cannot be in the West Hall. Therefore the Compass is in the South Hall, and clue 3 puts the Drum in the North Hall (opposite South). Clue 1 puts the Turtle in the East Hall (South is taken), and the Kite takes the last hall, the West Hall — which clue 4 allows.

SOLUTION: North Hall — Painted Drum; East Hall — Jade Turtle; South Hall — Brass Compass; West Hall — Silver Kite. This case has exactly one solution.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
