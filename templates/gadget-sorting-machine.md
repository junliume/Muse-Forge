# The Gadget Sorting Machine

*Sort inventions with AND, OR and NOT — checked rules, no wrong answers*

**Category:** Games · **Ages:** Ages 8–12 · **Chinese name:** 小发明分拣机 · **Spec version:** 1.0

## What it is

An original Boolean-logic sorting game. Each invention card shows three honest traits — Is it metal? Does it have wheels? Does it make a sound? — and the sorting machine's two gates decide its bin: the Gold Bin takes Metal AND Sound, the Blue Bin takes Wheels AND NOT Metal, and everything else slides to the Return Tray to be re-checked. Players say the rule out loud for every card before it drops, and the machine shows its gate check so a disagreement is settled by the rule, never by speed. No timers, no lives, no ranking.

## Features

- Three-trait invention cards — metal, wheels, sound, always shown honestly
- Two gates with AND and NOT — say the rule aloud before each drop
- Machine gate-check replay — every sort can be re-checked step by step
- Challenger mode — a second player sets a secret rule change for the next round
- No timers, no lives, no ranking — reasoning only

## What's included

- Sorting machine board & two gates
- 8-card starter deck (all trait combinations)
- Gate-check replay
- Challenger rule-change mode

## At a glance

- Eight invention cards on the bench, each showing metal, wheels and sound traits at a glance
- The two gates lit up: Gold takes Metal AND Sound, Blue takes Wheels AND NOT Metal
- The gate-check moment: a card re-checked trait by trait until the rule settles its bin

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Player's name** (text) — The sorter is cheered on by this name
  - Default: Alex
- **Rule style** (single)
  - Choices: Starter rules / Tricky NOTs / Expert gates
  - Default: Starter rules
- **Machine theme** (single)
  - Choices: Workshop benches / Harbour crates / Garden sheds
  - Default: Workshop benches
- **Cards per round** (single)
  - Choices: 8 cards / 12 cards
  - Default: 8 cards
- **Play mode** (single)
  - Choices: Solo sorter / Two-player challenger
  - Default: Solo sorter
- **Game language** (single)
  - Choices: English / Chinese (中文) / Spanish (Español)
  - Default: English
- **Session length** (single)
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Hint style** (single)
  - Choices: Ask a guiding question / Show one gate / Let me try twice first
  - Default: Ask a guiding question
- **Parent view** (single)
  - Choices: Sorts + rule checks summary / Session summary only
  - Default: Sorts + rule checks summary

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Tricky NOTs with 12 cards for a two-player game, about 20 minutes
- Keep starter rules but use the harbour crates theme, and show one gate as the hint
- Starter session in Chinese, about 10 minutes, solo sorter

## Sample content

### Sample · Round 1: Eight Inventions, Two Gates (fully worked round)

SET-UP — THREE TRAITS, TWO GATES: Every invention card shows three honest traits, always printed on the card: Is it metal? Does it have wheels? Does it make a sound? The sorting machine has two gates. The Gold Bin takes a card when Metal AND Sound are both true. The Blue Bin takes a card when Wheels is true AND Metal is NOT true. Every card that fits neither gate slides to the Return Tray, to be re-checked — never thrown away, never argued about. Before each card drops, the sorter says the rule out loud; if anyone disagrees, the machine re-checks the card trait by trait until the rule settles it.

CARD 1 — TIN WHISTLE TRIKE: metal YES, wheels YES, sound YES. Gold gate: Metal AND Sound is true → GOLD BIN.

CARD 2 — STEEL SILENT DELIVERY CART: metal YES, wheels YES, sound NO. Gold needs sound — false; Blue needs NOT metal — false → RETURN TRAY (Gold needs sound; Blue needs NOT metal).

CARD 3 — BRASS HAND BELL: metal YES, wheels NO, sound YES. Gold gate: Metal AND Sound is true → GOLD BIN.

CARD 4 — IRON QUIET KETTLE: metal YES, wheels NO, sound NO. Gold needs sound — false; Blue needs wheels and NOT metal — false → RETURN TRAY.

CARD 5 — PINEWOOD SINGING CART: metal NO, wheels YES, sound YES. Blue gate: Wheels AND NOT Metal is true → BLUE BIN (Gold needs metal).

CARD 6 — WOODEN QUIET WAGON: metal NO, wheels YES, sound NO. Blue gate: Wheels AND NOT Metal is true — Blue does not ask about sound → BLUE BIN.

CARD 7 — PAPER SONG HORN: metal NO, wheels NO, sound YES. Gold needs metal — false; Blue needs wheels — false → RETURN TRAY (Gold needs metal; Blue needs wheels).

CARD 8 — CLAY QUIET GARDEN STONE: metal NO, wheels NO, sound NO. Neither gate can take it → RETURN TRAY.

CLOSING TALLY: Gold Bin 2, Blue Bin 2, Return Tray 4 — 8 cards sorted. CLOSING CHECK: these 8 cards are exactly the 8 possible trait combinations — every mix of metal or not, wheels or not, sound or not appears exactly once — so the two gates have been tested on the whole truth table, and every bin agrees with the rules.

TRY IT: a new card arrives — the Copper Singing Kettle: metal YES, wheels NO, sound YES. Sort it by saying both gates out loud first, then let it drop.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
