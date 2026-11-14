# Lantern Logic: Truth-Tellers & Tricksters

*Gentle logic puzzles where you deduce who is telling the truth*

**Category:** Games · **Ages:** Ages 8–12 · **Chinese name:** 灯笼逻辑 · **Spec version:** 1.0

## What it is

A cozy deduction game of lantern keepers, hidden fireflies and clues that cannot all be true. Each round gives a small, fair puzzle — three lanterns, three keepers, or a short who-did-it — where exactly one clue pattern fits, and the player proves the answer step by step instead of guessing. Hints reveal one line of the truth table at a time, never the answer outright. No timers, no losing state: a wrong turn just lights the next hint.

## Features

- Step-by-step truth-table hints, never the answer outright
- Every puzzle verified to have exactly one solution
- Solo, co-op and whole-family play modes
- Parent view with full worked solutions
- No timers, no fail state, no ranking

## What's included

- Puzzle engine with verified single solutions
- Truth-table hint system
- Worked-solution parent view
- Co-op discussion prompts

## At a glance

- Three lanterns, three clues — exactly one clue is true, prove which lantern holds the firefly
- Hints light one truth-table row at a time, so the deduction stays yours
- Co-op mode: each player argues for one keeper, then the table settles it together

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The puzzles greet the player by this name
  - Default: Alex
- **Age band** (single)
  - Choices: Ages 7–8 / Ages 8–10 / Ages 10–12
  - Default: Ages 8–10
- **Puzzle types** (multi)
  - Choices: Truth-teller puzzles / Lantern & box clues / Who-did-it deduction / Sequence logic
  - Default: Truth-teller puzzles, Lantern & box clues
- **Difficulty** (single)
  - Choices: Gentle / Steady deduction / Challenge
  - Default: Steady deduction
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Hints** (single)
  - Choices: Plenty of hints / Some hints / Minimal hints
  - Default: Plenty of hints
- **Play mode** (single)
  - Choices: Solo / Co-op with a partner / Whole family
  - Default: Solo
- **Language** (single)
  - Choices: English / English + Chinese help button / Chinese (中文) / Spanish / Japanese / Korean
  - Default: English

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a younger player, gentle difficulty, about 10 minutes, with plenty of hints
- Co-op with a partner, who-did-it deduction puzzles, challenge difficulty
- Whole family mode, about 20 minutes, English with a Chinese help button

## Sample content

### Sample Puzzle · The Three Lanterns (complete worked puzzle with truth table)

WARM-UP (say it aloud): A clue can be true or false — our job is not to believe clues, it is to test them.

THE PUZZLE: Three lanterns stand on the harbour wall: Red, Blue and Gold. Exactly one lantern holds the firefly. Each lantern carries one clue, and EXACTLY ONE clue is true — the other two are false.
Red lantern clue: 'The firefly is in the Gold lantern.'
Blue lantern clue: 'The firefly is not in the Red lantern.'
Gold lantern clue: 'The firefly is not in the Gold lantern.'

TEST EACH POSSIBILITY (the truth table):
Case 1 — Firefly in Red: Red clue is FALSE (it is not in Gold) ✓, Blue clue is FALSE (it IS in Red, so 'not in Red' is false) ✓, Gold clue is TRUE (it is not in Gold) ✓. That is exactly one true clue — this case FITS.
Case 2 — Firefly in Blue: Red clue FALSE ✓, Blue clue TRUE (it is not in Red), Gold clue TRUE (it is not in Gold). That is two true clues — this case FAILS the 'exactly one true' rule.
Case 3 — Firefly in Gold: Red clue TRUE, Blue clue TRUE, Gold clue FALSE. That is two true clues — this case FAILS.

SOLUTION: Only Case 1 fits, so the firefly is in the RED lantern — proved, not guessed.

TRY IT YOURSELF (answer for the parent view): Two keepers, Bram and Cleo. Exactly one always tells the truth and the other always lies. Bram says 'Cleo is the liar.' Cleo says 'I am the truth-teller.' Worked answer: If Bram were the liar, his statement would be false, so Cleo would not be the liar — but there is exactly one liar, contradiction. So Bram is the truth-teller, Cleo is the liar, and her statement is false, which fits.

Closing line: In Lantern Logic you never have to guess — if a case breaks the rule, cross it out and keep going.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
