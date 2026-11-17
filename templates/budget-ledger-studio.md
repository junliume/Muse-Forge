# The Budget Ledger Studio

*A calm monthly ledger that shows where the money went — and what to try next month*

**Category:** Grown-ups · **Ages:** Adults · **Chinese name:** 家庭账本工作室 · **Spec version:** 1.0

## What it is

A quiet, judgement-free studio for keeping a household budget in one monthly ledger. You set a small number of spending categories, record income and outgoings as they happen (or in one weekly catch-up), and at month's end the studio lays out a plain review: what came in, what went out, which categories ran over or under, and one or two gentle, specific suggestions for next month. There are no scores, no streaks and no red warnings — a month over budget is information, not a failure. Everything is entered with placeholder-friendly examples, works in a single currency, and can be exported as a simple summary you can keep or share with a partner.

## Features

- One monthly ledger: income, fixed bills and everyday spending in a single view
- Few categories by design — six to ten, named in your own words
- Weekly catch-up mode: enter a week of spending in a few minutes from receipts or memory
- Month-end review that compares plan with actual, category by category, in plain language
- Rollover choices per category: carry a surplus forward, or start each month fresh
- One or two concrete next-month suggestions, sized in real amounts, never a lecture
- Exportable one-page monthly summary for sharing or filing

## What's included

- Monthly ledger engine
- Category and fixed-bill setup
- Weekly catch-up entry flow
- Plan-versus-actual review
- Rollover and next-month suggestion tools
- One-page summary export

## At a glance

- A month at a glance: in 3,200 — out 2,940 — kept 260, with groceries over by 40 and transport under by 55
- A suggestion with a number on it: moving 30 from the eating-out plan to groceries matches how the last two months actually went
- Fixed bills listed once, checked monthly — a bill that changes amount is flagged for a second look

## How it works

1. Set up income, fixed bills and a short list of spending categories with a planned amount for each
2. Record spending as it happens, or in one weekly catch-up sitting
3. At month's end, read the plain review: plan versus actual, category by category
4. Choose rollovers and accept, edit or ignore the next-month suggestions — then the new month opens

## Customization questions

Ask these one at a time and use the answers given; the default is shown for each.

- **Household display name** (text) — Placeholder only — shown at the top of the ledger
  - Default: Our Household
- **Currency** (single) — All amounts are shown in this one currency
  - Choices: US dollars / Euros / Pounds sterling / Canadian dollars / Australian dollars
  - Default: US dollars
- **Categories** (multi) — Kept short on purpose; name them in your own words in deep customization
  - Choices: Groceries / Eating out / Transport / Home and utilities / Health / Fun and hobbies / Kids and family / Gifts and giving
  - Default: Groceries, Transport, Home and utilities, Fun and hobbies
- **Entry rhythm** (single) — How spending usually gets recorded
  - Choices: As it happens / Weekly catch-up / Month-end catch-up
  - Default: Weekly catch-up
- **Review day** (single) — When the month-end review is prepared
  - Choices: Last day of the month / First day of the new month / A chosen weekday each month
  - Default: First day of the new month
- **Rollover style** (single) — What happens to a category surplus
  - Choices: Carry forward per category / Start fresh each month / Ask me each month
  - Default: Ask me each month
- **Suggestion style** (single) — How next-month suggestions are phrased
  - Choices: Gentle and brief / Detailed with amounts / Off — review only
  - Default: Gentle and brief
- **Sharing** (single) — Who the monthly summary is prepared for
  - Choices: Just me / Me and a partner / Whole household
  - Default: Just me

## Deep customization examples

Things a user might ask for in their own words, beyond the questions above:

- Rename the categories to match our real life, add one for the car, and keep everything in euros
- Month-end catch-up only, detailed suggestions with amounts, and a summary my partner and I both read
- Track a savings goal alongside the ledger and show it first in every review

## Sample content

### Sample Month · March in the Ledger: Setup, a Weekly Catch-Up, and the Month-End Review (complete worked example)

SETUP. The household plans in US dollars with six categories. Income: 3,200 a month. Fixed bills: rent 1,200, utilities about 110, phone 45, subscriptions 28. Spending plans: groceries 520, eating out 160, transport 140, home bits 90, fun and hobbies 120, gifts and giving 50. The plan leaves about 237 unassigned on purpose — a plan that spends every last unit on paper leaves nothing for real life.

A WEEKLY CATCH-UP. Sunday evening, ten minutes, receipts and memory. Groceries: market 86, supermarket 54 — 140 for the week. Eating out: one lunch 18, one family dinner 47 — 65. Transport: fuel 38, two bus fares 6 — 44. Home bits: light bulbs and cleaning things, 16. Fun: a paperback 14 and a streamed film 6 — 20. Each entry takes one line: date, category, amount, a few words. Nothing is judged as it is typed.

THE MONTH-END REVIEW. April 1, the review opens in plain sentences. In: 3,200. Out: 2,940. Kept: 260. Category by category: groceries planned 520, spent 560 — over by 40, the second month in a row, both times in the last week of the month. Eating out planned 160, spent 132 — under by 28. Transport planned 140, spent 85 — under by 55; two planned trips did not happen. Fixed bills all matched except utilities, 118 against an expected 110 — worth a second look next month, not a worry yet.

THE SUGGESTIONS. Two, both with numbers. First: the pattern says the grocery plan is simply 40 too small — move 30 from eating out (which has run under twice) and 10 from the unassigned amount, and set groceries to 560. Second: transport's 55 surplus — carry 25 forward for next month's planned trip and let the other 30 join the kept amount. The household accepts the first, edits the second to carry all 55 forward, and ignores nothing else because there is nothing else — two suggestions is the whole list.

THE NEW MONTH OPENS. April's ledger starts with the adjusted grocery plan, transport carrying its 55, and a one-line note pinned at the top: utilities to double-check. The kept 260 moves to the household's savings note. Total time spent on the month's money: about an hour, in small pieces, with no spreadsheets and no arguments — just a ledger that says what happened and one or two ideas for what to try next.

## Build notes

Build as a static Space unless stored data is needed; if the spec implies saved state, build fullstack with empty tables. Start from the sample content below as the seed example, and use placeholders (never real personal data) wherever the spec shows a sample name.
