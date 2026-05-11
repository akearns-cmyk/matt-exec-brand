# CLAUDE.md — Executive Brand System

This is Matt's executive brand operating system.
It produces content that sounds like him, serves his audience, and compounds over time.

---

## How This System Works

The system is built in layers. Each layer depends on the one below it.
Do not skip layers. Do not generate Layer 4 output without running Layer 2–3 first.

```
Layer 1 — Foundation (always loaded)
    foundation/point-of-view.md
    foundation/audience-delight.md
    foundation/creator-style.md

Layer 2 — Raw Material → Usable Insight
    skills/layer-2/insight-extractor.md

Layer 3 — Usable Insight → Polished Draft
    skills/layer-3/hook-creator.md
    skills/layer-3/post-enricher.md

Layer 4 — Polished Draft → Published Content
    skills/layer-4/linkedin-drafter.md
    skills/layer-4/newsletter-writer.md
    skills/layer-4/talk-abstract.md

Layer 5 — Performance → System Improvement
    skills/layer-5/monthly-review.md
```

---

## Before Every Session

**Always load these three files before doing anything else:**

1. `foundation/point-of-view.md` — Matt's core beliefs and POV pillars
2. `foundation/audience-delight.md` — Who he's writing for and what they need
3. `foundation/creator-style.md` — How he writes: voice, rhythm, vocabulary, rules

These are not optional. Every skill references them. Content produced without them will drift.

---

## Standard Workflows

### "I have a raw idea / brain dump / voice memo"
1. Run `skills/layer-2/insight-extractor.md`
2. Pick the recommended insight
3. Run `skills/layer-3/hook-creator.md`
4. Run the chosen hook through `skills/layer-3/post-enricher.md`
5. Run the enriched draft through the appropriate Layer 4 skill

### "I need a LinkedIn post"
1. State the insight in one sentence
2. If no hook exists yet → `hook-creator.md`
3. Rough draft → `post-enricher.md`
4. Final → `linkedin-drafter.md`

### "I need a newsletter issue"
1. Confirm the through-line (one sentence)
2. Source material → `insight-extractor.md` (if raw)
3. Draft → `newsletter-writer.md`
4. Voice check → `post-enricher.md` (Lens 3 only if already polished)

### "I need a talk abstract"
1. State the talk's core argument in one sentence
2. Run `talk-abstract.md`
3. Check against `point-of-view.md` for pillar alignment

### "It's the end of the month"
Run `skills/layer-5/monthly-review.md`
Act on any foundation file updates before the next month begins.

---

## Rules Claude Must Follow in Every Session

### Do
- Load all three foundation files at session start
- Follow the layer order — don't jump from raw input to final output
- Reference the specific POV pillar that each piece of content serves
- Check all output against `creator-style.md` before presenting it as final
- Tell Matt when something is off-brand and why — specifically
- Ask the single most important question before drafting, not ten questions

### Do Not
- Generate content that uses vocabulary from the "avoid" list in `creator-style.md`
- Skip the insight extraction step when working from raw material
- Present a first draft as publish-ready
- Add hedges, caveats, or qualifications that Matt didn't ask for
- Use generic enthusiasm ("Great idea!", "This is really insightful")
- Produce a 10-point list when 3 points would be stronger
- Open any post with "I" as the first word (LinkedIn rule)
- End any post with "Thoughts?" (weak CTA)

---

## File Editing Protocol

### When to edit a foundation file
Only edit foundation files when:
- The monthly review (`layer-5/monthly-review.md`) recommends a specific update
- Matt explicitly says a pillar has changed
- A pattern of content drift has been identified and traced back to an inaccurate foundation

### How to edit a foundation file
1. State what you're changing and why before making the change
2. Show the before and after for the specific section
3. Update the "Last updated" line with the current date
4. Note in the monthly review log what was updated

### Do not edit foundation files
- Based on a single post's performance
- To make content production easier (simplifying the constraints)
- Without Matt's explicit approval

---

## Folder Structure

```
exec-brand-system/
├── CLAUDE.md                          ← You are here
├── foundation/
│   ├── point-of-view.md              ← Layer 1: Matt's beliefs
│   ├── audience-delight.md           ← Layer 1: Who he serves
│   └── creator-style.md              ← Layer 1: How he writes
└── skills/
    ├── layer-2/
    │   └── insight-extractor.md      ← Raw → Insight
    ├── layer-3/
    │   ├── hook-creator.md           ← Insight → Opening
    │   └── post-enricher.md          ← Draft → Authentic draft
    ├── layer-4/
    │   ├── linkedin-drafter.md       ← → LinkedIn post
    │   ├── newsletter-writer.md      ← → Newsletter issue
    │   └── talk-abstract.md          ← → Talk submission
    └── layer-5/
        └── monthly-review.md         ← Performance → System update
```

---

## Content Principles (The Short Version)

**On voice:** If a stranger could have written it, it isn't done.

**On insight:** If it confirms what the reader already believes, it isn't interesting.

**On structure:** If it takes more than one sentence to say what the piece is about, it isn't ready to write.

**On length:** As long as it needs to be. Not one word more.

**On performance:** Resonance matters more than reach. One reader who forwards it matters more than a thousand impressions.

---

## Getting Started

If the foundation files are blank (first use), start here:

1. Open `foundation/point-of-view.md` and fill in Matt's core belief and at least 3 POV pillars
2. Open `foundation/audience-delight.md` and fill in the primary audience profile and their top 3 fears
3. Open `foundation/creator-style.md` and fill in Voice in Three Words, his vocabulary preferences, and at least 2 structural patterns he uses

Once the foundation is filled in, the system is ready.

---

*System version: 1.0*
*Built: [DATE]*
*Next review: [First Monday of next month]*
