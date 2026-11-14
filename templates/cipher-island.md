# Cipher Island

*Crack gentle codes, unlock the island, one clue at a time*

**Category:** Games · **Ages:** Ages 7–11 · **Chinese name:** 密码岛 · **Spec version:** 1.0

## What it is

A gentle code-breaking adventure on a friendly island. Each level gives the player one clear code system, a printed key they can always see, and a short message to crack — no timers, no failing, and hints that teach the method instead of giving the answer away. Early levels use a simple letter-shift code, later levels add symbol swaps and word scrambles, always one new idea at a time. Solving a message unlocks the next part of the island story, so decoding always feels like progress, not a test.

## Features

- One code system at a time, with the key always visible
- No timers and no fail state — hints teach the method
- Island story unlocks message by message
- Play solo, with a partner, or as a whole family
- Parent view: levels completed and code types mastered

## What's included

- 12-level island adventure
- Printable code-key cards
- Hint system that teaches the method
- Parent progress view

## At a glance

- One code at a time — the key stays on screen, so it is thinking, not guessing
- No timers, no fail state: a wrong letter just wiggles and invites another try
- Every cracked message unlocks the next corner of the island story

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The island messages will greet the player by this name
  - Default: Alex
- **Age band** (single) — Sets message length and vocabulary
  - Choices: Ages 7–8 / Ages 9–11
  - Default: Ages 7–8
- **Code types to include** (multi) — One new type is introduced at a time
  - Choices: Letter-shift codes / Symbol swap codes / Word scrambles / Number codes
  - Default: Letter-shift codes, Symbol swap codes
- **Difficulty** (single) — Gentle keeps messages to 3–5 words
  - Choices: Gentle / Standard / Tricky
  - Default: Gentle
- **Session length** (single) — How many messages fit in one sitting
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Play mode** (single) — Partner and family modes split the decoding jobs
  - Choices: Solo / With a partner / Whole family
  - Default: Solo
- **Game language** (single) — Messages and instructions in this language
  - Choices: English / Chinese (中文) / English + Spanish / English + Japanese / English + Korean
  - Default: English
- **Hints** (single) — Hints teach the method, never just reveal the answer
  - Choices: Plenty of hints / Some hints / Minimal hints
  - Default: Plenty of hints

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Gentle difficulty for a 7-year-old, letter-shift codes only, plenty of hints, about 10 minutes
- Standard difficulty with symbol swaps and word scrambles, partner mode for two players
- Tricky messages in English with minimal hints for a confident 10-year-old

## Sample content

### Sample · Level One: The Message in the Bottle (complete worked level)

THE SETUP: Alex washes ashore on Cipher Island and finds a bottle on the sand. Inside is a note and a code key.

THE KEY (always visible): this level uses a letter-shift code of +2 — every real letter was moved 2 places forward in the alphabet to hide it (A became C, B became D, C became E, and so on, wrapping Z back to A). To decode, move each letter 2 places BACK.

MESSAGE 1: OGGV CV VJG QNF QCM. Work it letter by letter: O back 2 is M, G back 2 is E, G is E, V back 2 is T — that spells MEET. Next word: C back 2 is A, V back 2 is T — AT. Next: V is T, J back 2 is H, G is E — THE. Next: Q back 2 is O, N back 2 is L, F back 2 is D — OLD. Last: Q is O, C is A, M back 2 is K — OAK. The message reads: MEET AT THE OLD OAK.

MESSAGE 2 (try it, then check): DTKPI VJG OCR. Decoding the same way gives: BRING THE MAP.

YOUR TURN: a third slip in the bottle reads NQQM DA VJG JCTDQWT — decode it with the key (answer for parents: LOOK BY THE HARBOUR).

LEVEL COMPLETE: the old oak on the hill lights up on the island map, and Level Two unlocks with a brand-new symbol key.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
