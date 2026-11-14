# Gear Train Workshop

*Predict, build and test spinning gear trains*

**Category:** Games · **Ages:** Ages 7–11 · **Chinese name:** 齿轮传动工坊 · **Spec version:** 1.0

## What it is

A hands-on puzzle workshop where players predict which way each gear will spin and how fast, build the train, then test it and explain what happened. Meshed gears always flip direction, and bigger gears turn more slowly — two simple rules that unlock surprisingly tricky chains, idler gears and design-your-own machines. No timers, no speed pressure: stars reward careful prediction and clear explanations, never fast clicking.

## Features

- Predict-Test-Explain on every level — guess first, then watch it spin
- Two true rules throughout: meshing flips direction, teeth set the speed
- Idler gears, jammed trains and design-your-own challenges
- No timers or speed rewards — careful thinking earns the stars

## What's included

- Gear puzzle engine (24 levels)
- Predict-Test-Explain level flow
- Design-your-own workshop
- Parent progress note

## At a glance

- Predict first: which way will the last gear spin — and how fast?
- Two rules unlock every puzzle: meshing flips direction, more teeth means slower turns
- Build your own train in the workshop, then test whether it really works

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The workshop notebook will use this name
  - Default: Alex
- **Age band** (single) — Sets chain length and ratio difficulty
  - Choices: Ages 7–8 / Ages 8–10 / Ages 10–11
  - Default: Ages 8–10
- **Language** (single)
  - Choices: English / English + Chinese (双语) / Chinese (中文) / Español / 日本語 / 한국어
  - Default: English
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 20 min / About 30 min
  - Default: About 20 min
- **Workshop theme** (single)
  - Choices: Clock Tower Workshop / Harbor Waterworks / Bakery Mill / Space Station Workshop
  - Default: Clock Tower Workshop
- **Challenge focus** (multi)
  - Choices: Direction flips / Speed & teeth ratios / Idler gears / Design-your-own trains
  - Default: Direction flips, Speed & teeth ratios
- **Help style** (single)
  - Choices: Predict-first hints / Worked example first / Gentle step-by-step
  - Default: Predict-first hints
- **Play mode** (single)
  - Choices: Solo / Co-op with a partner / Family challenge
  - Default: Solo

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For ages 7–8, about 10 minutes, in the Bakery Mill, focus only on direction flips with gentle step-by-step help
- Bilingual English and Chinese, about 30 minutes, Harbor Waterworks theme, add idler gears and design-your-own trains
- Solo play for ages 10–11 in the Clock Tower Workshop, about 15 minutes, speed and teeth ratios with predict-first hints

## Sample content

### Sample Level · Level 1 — Wake the Waterwheel (fully worked level)

HOW EVERY LEVEL WORKS: Predict (say the direction and speed before anything spins) → Build/Test (watch the train turn) → Explain (say why, in your own words). Two rules are always true: RULE 1 — When two gears mesh, they turn in OPPOSITE directions. RULE 2 — Speed trades with teeth: rpm of the driven gear = rpm of the driver × (driver teeth ÷ driven teeth). A gear with twice the teeth turns half as fast.

LEVEL 1 — WAKE THE WATERWHEEL. Story: The Clock Tower Workshop waterwheel has stopped. Connect the motor to the wheel and wake it up. The train, left to right: MOTOR M (12 teeth) meshes with GEAR A (24 teeth). GEAR A meshes with GEAR B (12 teeth). GEAR B meshes with GEAR C (18 teeth). The WATERWHEEL W sits on the same axle as Gear C, so W always turns exactly the same way and speed as C. The motor turns CLOCKWISE at 36 turns per minute (36 rpm).

PREDICT — Question 1 (direction): Which way does each gear turn? Work it with Rule 1, flipping at every mesh: M is clockwise. A meshes with M, so A is COUNTERCLOCKWISE. B meshes with A, so B is CLOCKWISE. C meshes with B, so C is COUNTERCLOCKWISE. The waterwheel is on C's axle, so W is COUNTERCLOCKWISE. Full answer: M clockwise, A counterclockwise, B clockwise, C counterclockwise, W counterclockwise.

PREDICT — Question 2 (speed): Use Rule 2 one mesh at a time. A: 36 × (12 ÷ 24) = 36 × 1/2 = 18 rpm. B: 18 × (24 ÷ 12) = 18 × 2 = 36 rpm. C: 36 × (12 ÷ 18) = 36 × 2/3 = 24 rpm. W = C, so the waterwheel turns at 24 rpm. Full answer: M 36 rpm, A 18 rpm, B 36 rpm, C 24 rpm, W 24 rpm. Notice the pattern: B ends back at 36 rpm because A halved the speed and B doubled it again — the middle gears can cancel out, but the directions never lie: count the flips.

TEST: Press Test and watch. The motor spins clockwise; A turns slowly the other way; B spins fast again; C and the waterwheel turn counterclockwise at a steady 24 rpm and the workshop bucket chain starts lifting. If a prediction was wrong, the level does not fail you — it highlights the exact mesh where the flip or the ratio went wrong and asks you to predict that one gear again.

EXPLAIN (model explanation a player can match in their own words): 'Every mesh flips the direction, so after three flips from the motor the wheel turns the opposite way to the motor. A has twice the motor's teeth so it turns half as fast, B gives the speed back, and C has one-and-a-half times B's teeth, so it keeps two-thirds of B's speed: 24 rpm.'

MINI-CHALLENGE (with checked answer): The keeper wants the waterwheel to turn CLOCKWISE instead, with everything else the same. What is the smallest change? ANSWER: Add ONE idler gear between B and C. One extra mesh adds one extra flip, so C and W become clockwise. Speeds: the idler passes speed through by the same Rule 2 twice and its own size cancels for the final speed, so C still ends at 24 rpm — direction changes, final speed does not. Verified: with idler D between B and C — D turns counterclockwise, C turns clockwise, W clockwise at 24 rpm.

PARENT NOTE: No timers anywhere. Stars are for a correct prediction or a clear explanation, never for speed. All names are placeholders and all machines are imaginary workshop inventions.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
