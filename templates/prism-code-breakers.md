# Prism Code Breakers

*Crack the colour code with pure deduction*

**Category:** Games · **Ages:** Ages 8–12 · **Chinese name:** 棱镜密码 · **Spec version:** 1.0

## What it is

A Mastermind-style colour-code deduction game where the player is the detective. Each round hides a short colour code; every guess earns honest clues — how many colours are right and in the right place, and how many are right but in the wrong place — and the player narrows the possibilities on a deduction grid until only one code can fit all the clues. No timers, no lives, no luck: a code is cracked by reasoning, and the end-of-round replay shows each clue doing its work.

## Features

- Deduction grid that crosses off impossible colours
- Honest place / wrong-place clues on every guess
- Worked replay showing how each clue narrowed the field
- Two-player codemaker mode — one player sets, one solves
- No timers, no lives, no ranking — reasoning only

## What's included

- Code board & colour pegs
- Deduction grid
- Worked replay
- Two-player codemaker mode

## At a glance

- A hidden 3-peg code and a row of guesses, each scored with place and wrong-place clues
- The deduction grid — colours crossed off, certainties circled, one column narrowing at a time
- The crack moment: the revealed code with a replay stepping through how every clue helped

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The detective is cheered on by this name
  - Default: Alex
- **Code length** (single) — How many pegs the hidden code has
  - Choices: 3 pegs / 4 pegs
  - Default: 3 pegs
- **Difficulty** (single) — How much the clues give away and how twisty the codes get
  - Choices: Starter clues / Classic codes / Expert codes
  - Default: Starter clues
- **Colour theme** (single) — The palette the code pegs wear
  - Choices: Prism colours / Ocean & sunset / Garden colours
  - Default: Prism colours
- **Play mode** (single) — Solve alone, or take turns as codemaker and detective
  - Choices: Solo detective / Two-player codemaker
  - Default: Solo detective
- **Language** (single) — The language the game speaks and prints
  - Choices: English / Chinese (中文) / Spanish (Español)
  - Default: English
- **Session length** (single) — Rounds are sized to fit the session
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Hint style** (single) — How much help appears when a code stays uncracked
  - Choices: Ask a guiding question / Show one deduction / Let me try twice first
  - Default: Ask a guiding question
- **Parent view** (single) — What parents see after each session
  - Choices: Deductions made + codes cracked / Session summary only
  - Default: Deductions made + codes cracked

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Make it a 4-peg expert code for a two-player game, about 20 minutes
- Keep 3 pegs but use the ocean and sunset colours, and show one deduction as the hint
- Starter clues in Chinese, about 10 minutes, solo detective

## Sample content

### Sample · Round 1: The Three-Peg Prism Code (fully worked round)

ROUND 1 — THE THREE-PEG PRISM CODE

The prism hides a code of 3 pegs. The colours are Ruby (red), Ocean (blue), Sunny (yellow) and Leaf (green), and no colour repeats in the code. Every guess is scored honestly with two numbers: how many colours are right AND in the right place, and how many colours are right but in the WRONG place. Detective Alex works on the deduction grid, crossing off what each clue makes impossible.

GUESS 1: Ruby, Sunny, Leaf → 1 in the right place, 1 right colour in the wrong place. Reasoning: Sunny sits in position 2 in both the guess and the code, so Sunny is placed — circle it. Ruby appears in the code but not in position 1, so Ruby belongs in position 2 or 3 — and position 2 is taken, so Ruby is position 3. Leaf is not in the code at all — cross Leaf off the whole grid.

GUESS 2: Leaf, Ocean, Sunny → 0 in the right place, 2 right colours in the wrong place. Reasoning: Ocean is in the code but not in position 2, so Ocean is position 1 or 3 — position 3 is already Ruby, so Ocean is position 1. Sunny is confirmed in the code but not in position 3, which fits position 2 exactly. Leaf is absent again, as the grid already says.

GUESS 3: Ruby, Leaf, Ocean → 0 in the right place, 2 right colours in the wrong place. Reasoning: this guess checks the deductions — Ruby is not in position 1 (it is 3), Ocean is not in position 3 (it is 1), and Leaf is absent once more. Every part of the clue agrees with the grid.

GUESS 4: Sunny, Ruby, Leaf → 0 in the right place, 2 right colours in the wrong place. Reasoning: Sunny is not in position 1, Ruby is not in position 2, and Leaf is absent a third time — Leaf is eliminated for certain, and nothing in this clue can move Ocean, Sunny or Ruby from where the grid has placed them.

SOLUTION: Ocean, Sunny, Ruby — the only code that fits all four guesses. CLOSING CHECK, scoring every guess against the solution: Guess 1 (Ruby, Sunny, Leaf): Sunny is placed, Ruby is present but misplaced, Leaf is absent → 1 in the right place, 1 in the wrong place ✓. Guess 2 (Leaf, Ocean, Sunny): Ocean and Sunny are both present but both misplaced, Leaf is absent → 0 and 2 ✓. Guess 3 (Ruby, Leaf, Ocean): Ruby and Ocean are both present but both misplaced, Leaf is absent → 0 and 2 ✓. Guess 4 (Sunny, Ruby, Leaf): Sunny and Ruby are both present but both misplaced, Leaf is absent → 0 and 2 ✓. All four clues match exactly — the code was cracked by reasoning, not by luck.

YOUR TURN — MINI-ROUND: A new 3-peg code is hidden from the same four colours, no repeats. Guess A: Ruby, Sunny, Ocean → 0 in the right place, 3 in the wrong place. Guess B: Ocean, Sunny, Ruby → 1 in the right place, 2 in the wrong place. Guess C: Sunny, Ocean, Ruby → 0 in the right place, 3 in the wrong place. Work the grid: Guess A says all three colours are in the code but every one is misplaced; Guess C then rules out the other arrangement of those three colours, and Guess B confirms the rest. One code fits all three guesses. (Reveal — read upside down or cover until you have solved it: the code is Ocean, Ruby, Sunny. Check it by scoring: against Guess A all three colours are present and all misplaced; against Guess B, Ocean is placed and the other two are misplaced; against Guess C all three are present and all misplaced — every clue matches.)

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
