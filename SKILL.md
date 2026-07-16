---
name: design-craft
description: A product/UX design-craft coach for any designer. Use when raising or checking the craft standard of a portfolio, case study, or presentation — visual hierarchy, typography, case-study writing, motion, design thinking, or catching AI-generic "slop." Distilled from ~75 top designer portfolios. Trigger on: "review my case study / portfolio / homepage", "does this look AI-generated", "help me write this project story", "what's wrong with this layout/type", "make this feel less generic".
---

# Product/UX Design Craft

A practical coach for keeping your **portfolio, case studies, and presentations** at a consistent, high standard — the kind that doesn't read as AI-generated or templated.

> 🚧 **Work in progress, built in public.** Released piece by piece — more worked before/after examples and visual diagrams are being added over time. If a section feels thin, it's not finished yet, not final.

Design school gives you the tools and methods. But real projects don't come with a correct route: every project has its own story, and the hard part is deciding how to solve it *and* how to express that. This skill is the reference guide for that middle — distilled from tearing apart ~75 strong designer portfolios.

## How to use

1. Name what you're working on: **layout/type**, **case-study writing**, **front-end/motion**, **how is the story telling**, or "**What else is missing**"
2. Jump to that section below. Apply the rules to the specific thing in front of you.
3. When reviewing existing work, run the **Anti-slop check** last — it catches what the others miss.

Golden rule that cuts across everything: **commit to a decision.** AI-generic design isn't ugly, it's *timid* — it hides in the safe middle. The fix is almost never a better tool; it's picking a lane and committing.

---

## 1 · Visual hierarchy & typography

- **Type scale: ~5 sizes, big jumps.** The hero should be roughly **4–6× the body**. Amateurs use fifteen sizes a few px apart and the page turns to mush. Pick a lane: disciplined-small (tiny 11px labels, tidy 20–26px headings) or dramatic-huge (120px+ hero). The mushy 24–40px middle is where it reads "AI-made."
- **Weight is a second axis.** Going black on two words dominates a line without changing its size. Use weight for emphasis before you reach for color.
- **Line-height & tracking — the fastest "generic → crafted" switch.** Big display: line-height ~0.9–1.05, tracking negative. Body: line-height 1.5–1.6. Small caps labels: add letter-spacing. As type gets bigger, tighten it; as it gets smaller, open it up.
- **One accent, spent once.** Commit to a single accent color with a real job; build the rest of the hierarchy from an opacity ladder of one neutral. Never the default framework palette (indigo-500, blue-600, green-400).
- **Real grid, pushed off-center.** Use uneven columns (2 : 1.5 : 2.5), hairline dividers as the skeleton — not equal thirds and drop-shadowed cards.
- **You control the eye path.** Size + contrast + position decide what someone sees first, second, third. Make that order deliberate.

## 2 · Case-study writing (the part most designers under-invest)

A case study isn't a report of *what you did* — it's the story of *how you thought*. A reviewer spends 15–40 seconds deciding whether you can think, not just execute. Four things carry that: a clear **structure**, visible **method**, real **storytelling**, and finally the sentence-level voice.

### 2a · The skeleton — what each beat has to do

Strong case studies move through these beats (loose order, not rigid headings):

1. **Context & role** — 2 lines: what it was, your role, the real constraint (timeframe / team / platform). Set the stakes fast.
2. **The real problem (reframe)** — the brief you were *handed* vs. the problem you *decided* to solve. This is the beat most portfolios skip, and the most important one. "The ask was X. The real problem was Y." Get this right and the whole study reads as "thinks about product," not "makes screens."
3. **Research → the one insight** — not "I ran interviews." The single thing you learned that *changed the direction*, anchored in a real observation or quote.
4. **Explore & decide** — what you tried, what you *killed*, and the trade-off you made. Show at least one rejected direction. Judgment lives here.
5. **Solution** — the design, narrated by *what each decision solves* — not a screenshot dump. Every hero shot answers a "why."
6. **Impact** — what changed, with a defensible number or a real signal. **Before → after** beats a lonely stat.
7. **Reflection** — one honest thing you'd change or learned. Specific, not "I'd iterate more."

Test: if someone reads only the **headings + first line of each beat**, they should still get the whole arc. Write for the skimmer first.

### 2b · Show the method — don't just name it

Naming methods (jobs-to-be-done, journey map, heuristic eval, card sort, usability test) signals fluency — but only if the method *changed something in the story*:

- **Tie each method to the decision it drove.** "The journey map showed the drop-off was at checkout, not signup — so I re-scoped." A journey map with no consequence is decoration.
- **Match the method to the question:**
  - *Discovery* (interviews, diary study, competitive teardown) → find the real problem
  - *Synthesis* (affinity mapping, personas, JTBD, journey map) → turn mess into a direction
  - *Ideation* (crazy-8s, How-Might-We) → widen before you narrow
  - *Validation* (usability test, A/B, click test) → prove or kill a direction
- **Include the failures the method caught.** "The first prototype tested badly — people couldn't find X — so I…" A method that never changed your mind reads fake.

### 2c · Make it a story, not a slide dump

- **One through-line.** Every strong case study has a spine — a tension raised early that everything resolves. If you can't say the project in one sentence ("How do you get strangers to trust each other enough to meet?"), the reader can't either.
- **Structure around the problem's difficulty, not your UI screens.** Tension → resolution, not feature → feature.
- **Show, don't tell.** "Users were frustrated" is telling. "One person closed the app mid-checkout and said 'I'll just call them'" is showing.
- **Pace it.** Lead with a one-line TL;DR of the outcome so skimmers get the payoff; let the deep dive be optional.
- **You are the narrator.** First person, a point of view, the stakes *you* felt. Neutral third-person reads like a template.

### 2d · Sentence-level voice (the finish)

- **The master test:** *"Could I paste this sentence into a different project — or a different designer's — unchanged?"* If yes, it's slop. Rewrite until it's only true here.
- **Specificity = humanity.** Swap vague nouns ("users," "friction," "the platform") for the concrete thing only this project has — a real person, a real quote, a real number.
- **Open with a moment or a tension, never a trend.** Not "In today's fast-paced world…" — a specific event, contradiction, or stake.
- **Show the road not taken.** A designer who only says "I chose the better option" reads junior. Say what you gave up and why: "The obvious move was X. I went with Y, and here's the cost."
- **Insight = overturning your own assumption.** Not "users wanted X" — "I assumed A, the research said B."
- **Numbers live inside sentences,** not in hollow 3-column stat grids. And source them, or cut them.

## 3 · Front-end craft & motion

- The tells of "AI-generated" front-end: centered stacked sections, default palette, flat `shadow-md`, uniform 16px radius, same font for heading and body, everything fading in at once.
- Bespoke moves: asymmetric grid + hairline dividers; genuine display/body font pairing with extreme weight contrast; **layered, color-tinted shadows**; a subtle noise texture; restraint — *not everything animates.*
- **Motion grammar:** micro-interactions 100–150ms, UI feedback under 300ms, entrances with an ease-out curve. Only animate `transform` and `opacity`. Always respect `prefers-reduced-motion`. Reserved motion reads premium; reveal-everything reads AI.

## 4 · Talking about your design thinking (interviews & presentations)

- Senior-level judgment is about **articulating decisions**, not pushing pixels. "They wanted to dissect my decision-making, not my designs."
- **Reframe first, then solution.** Most portfolios jump straight to the solution. Lead with how you redefined the problem — that one move turns "can design" into "can think about product."
- **Surface trade-offs before you're asked.** Naming a downside, and a thing you'd change, is one of the strongest maturity signals.
- **Turn adjectives into rules.** "Minimal / intuitive / clean" say nothing. "Max 3 primary actions on the driving screen, everything else one level down" is a real principle — it can be violated.

## 5 · Anti-slop check (run this on any finished piece)

Ban on sight, and ask what to reach for instead:

| Slop signal | Why it's empty | Reach for |
|---|---|---|
| "logic meets care", "with intention", "built to serve" | true of any designer; no stance | a claim with on-page evidence |
| "seamless / intuitive / minimal" | aspiration, not a decision | the trade-off you made to get there |
| triple-adjective stacks ("functional, inclusive, honest") | rule-of-three virtues, none proven | one claim, then demonstrate it |
| "leverage / utilize / robust" | corporate filler | plain verbs: use, build, made |
| "In today's world…" | throat-clearing | delete; start at the real point |
| unsourced big stats (40B+, 63%) | "says who?" | cite source + year, or cut |
| type stuck 24–40px, one centered column | timidity | commit — go big or go small |
| any sentence reusable across two projects | the master test failing | rewrite until only true here |

---

_This skill is a general, portable distillation. It pairs with a fuller course set (visual hierarchy, case-study writing, front-end/motion, design thinking, AI-UX) if you want the worked examples and teardowns._
