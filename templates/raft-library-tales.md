# The Raft Library Tales

*A floating raft library that drifts one gentle story at a time*

**Category:** Storytelling · **Ages:** Ages 4–8 · **Chinese name:** 木筏图书馆故事 · **Spec version:** 1.0

## What it is

A co-created storytelling app aboard a small wooden raft that is also a library: shelves along the railing, a reading bench in the shade of a striped sail, and a river that carries the raft to one new bank each evening. The child chooses where the raft ties up, picks a book from the shelf, and helps steer what happens inside its story — the narrator tells a short passage, stops at a real choice, and waits for the child to decide or invent what comes next. Every tale is built fresh from the child's choices, stays gentle and unhurried, and ends tied up safely for the night with one line the child said themselves kept as the story's last page.

## Features

- One river stop per session: a reed bank, a stone bridge, a watermill, a heron marsh
- Pick a book from the raft shelf — its cover sets the tale's kind, never its plot
- Tell, stop, choose: short passages with a real choice or invention at every stop
- The child's own words come back as the story's final line each night
- Gentle stakes only: lost hats, late ferries, shy fireflies — never peril or villains
- A river map that fills in one stop at a time, as a keepsake rather than a score
- Read-aloud friendly: short sentences, clear pauses, no dense paragraphs for young listeners

## What's included

- Raft library story engine
- River map of stops
- Shelf of story-starter book covers
- Choice-and-invention prompts
- Keepsake page of the child's own closing lines
- Parent view of finished tales

## At a glance

- Tie up at one new bank each evening and pick a book from the raft shelf
- The narrator tells a little, stops, and the child chooses or invents what happens next
- The tale ends safely tied up, with the child's own words as its last page

## How it works

1. Choose tonight's river stop and tie up the raft
2. Pick a book from the shelf by its cover
3. Listen to a short passage, then choose or invent what happens next
4. Reach the last page, add the child's own closing line, and shelve the tale on the river map

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Storyteller's name** (text) — The tales will call the child by this name
  - Default: Alex
- **Age band** (single) — Sets sentence length, story length and choice size
  - Choices: Ages 4–5 / Ages 5–6 / Ages 6–8
  - Default: Ages 5–6
- **Story language** (single) — Bilingual options add a help line, never a full translation dump
  - Choices: English / English + Chinese / English + Spanish
  - Default: English
- **River stops to visit** (multi) — Pick one or more — the raft rotates through them
  - Choices: Reed banks / Stone bridges / Watermills / Heron marshes / Orchard landings
  - Default: Reed banks, Stone bridges
- **Tale kinds** (multi) — The shelf stocks more of the kinds chosen
  - Choices: Helpful errands / Small mysteries / Silly mishaps / Quiet wonders
  - Default: Helpful errands, Quiet wonders
- **Choices per tale** (single) — More choices mean a longer, more child-steered tale
  - Choices: 2 choices / 3 choices / 4 choices
  - Default: 3 choices
- **Session length** (single) — One river stop per session
  - Choices: About 10 min / About 15 min / About 20 min
  - Default: About 15 min
- **Narration pace** (single) — Slower adds longer pauses and repeats key lines once
  - Choices: Slow and cosy / Steady / Lively
  - Default: Slow and cosy
- **Ending style** (single) — How each tale ties up for the night
  - Choices: Child's own closing line / A gentle goodnight rhyme / Both
  - Default: Child's own closing line

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- For a younger listener, reed banks only, 2 choices, slow and cosy, about 10 minutes
- Bilingual in English and Chinese, watermills and heron marshes, silly mishaps, about 20 minutes
- Lively pace with 4 choices and a goodnight rhyme at the end of every tale

## Sample content

### Sample Tale · The Book That Hummed at the Stone Bridge (complete worked tale)

TONIGHT'S STOP. The raft drifts until the water slows, and there it is: a stone bridge with three round arches, and steps going down to a tiny landing. We tie the rope to the iron ring, the way we always do — two loops, one knot — and the raft settles. On the shelf, one book is humming. Only a little. Books on this raft hum when they want to be opened, so we open it.

FIRST PAGE. Under the bridge, in the cool green shade of the middle arch, a water vole named Bramble kept a lending shelf of his own: six smooth pebbles, each one painted with a picture, each one a story you could borrow for a day. But this morning Bramble had a problem. A duckling had borrowed the pebble with the rainbow painted on it — and the duckling had taken it to show her brothers, and her brothers had taken it to show the far bank, and now nobody could remember which bank the rainbow pebble was on. "A borrowed story should always come home," said Bramble. "But my legs are short, and the river is long."

THE CHOICE. This is where the tale stops and waits for you. Does the raft help Bramble by: A) Asking the bridge swallows, who see every bank from above? B) Floating slowly downstream and calling at each bank, one by one? C) Painting a brand-new rainbow pebble together, so the shelf is whole again while the old one travels home in its own time? There is no wrong choice — but each one makes a different story. (In this telling, we choose A.)

IF WE ASK THE SWALLOWS. The swallows under the bridge fly in loops and land in a line, the way swallows do when they have news. "Rainbow?" says the oldest swallow. "We saw a rainbow that fits in a bill. Far bank, by the willow roots, where the ducklings nap." So the raft unties — two loops undone, one knot slipped — and drifts the short way to the willow roots, and there, in a neat row on a flat stone, are three ducklings asleep in the sun, and in front of them, where they had set it up like a tiny cinema screen, is the rainbow pebble. They were not keeping it. They were watching it, the way you watch a story you love. Bramble does not scold them — a good librarian never scolds a reader. Instead he says the rule out loud, kindly: "Borrow it, love it, bring it home by supper." The ducklings carry the pebble back themselves, swimming in a line, taking turns, and Bramble paints a small gold star on its back, so everyone will know this is the pebble that travelled furthest and still came home.

LAST PAGE. The raft ties up again under the bridge — two loops, one knot — and the shelf is whole, and the river goes dark and quiet one colour at a time. And the last line of tonight's tale is yours to say, in your own words. (Kept example: "The rainbow came home, and everybody got to watch it twice.")

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
