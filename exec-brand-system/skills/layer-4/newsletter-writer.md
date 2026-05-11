# Newsletter Writer — Layer 4 Skill

> **Purpose:** Draft a complete newsletter issue — one through-line, one audience, one clear outcome.
> The newsletter is where Matt goes deeper than LinkedIn allows.
>
> **Depends on:** `foundation/creator-style.md`, `foundation/audience-delight.md`, `foundation/point-of-view.md`
> **Typically follows:** `insight-extractor.md`, `hook-creator.md`, `post-enricher.md`

---

## When to Use This

- Matt has a developed insight worth 400–800 words of depth
- A LinkedIn post performed well and the newsletter goes deeper
- There's a framework, story, or pattern that needs room to breathe
- Monthly cadence: a scheduled send needs to go out

---

## Newsletter Identity

**Name of newsletter:** [FILL IN]
**Tagline / promise:** [FILL IN — e.g., "One idea for leaders who'd rather think than scroll."]
**Send frequency:** [FILL IN — e.g., "Every other Tuesday"]
**Reader expectation:** [FILL IN — e.g., "They open it expecting to be challenged on something they assumed was settled."]

---

## Input Format

**This issue's core insight:**
```
[One sentence]
```

**Source material:** *(paste enriched draft, bullet points, or raw notes)*
```
[PASTE HERE]
```

**Issue type:**
[ ] Deep dive on a framework
[ ] Story-driven lesson
[ ] Field notes (observations from recent work)
[ ] Response to something happening in the world/industry
[ ] Reflection / honest take
[ ] Interview or conversation excerpt

**Any sections to include:**
[ ] Opening hook + context
[ ] The core idea (body)
[ ] One concrete example
[ ] What this means for the reader
[ ] One thing to try / consider
[ ] Signoff

---

## Newsletter Structure Rules

### Every issue has ONE through-line
If you can't say what this issue is about in one sentence, it isn't ready to write.

### Sections and their jobs

| Section | Word target | Job |
|---|---|---|
| **Opening** | 40–80 words | Earn the read. Don't recap the world. Start in the idea. |
| **The Setup** | 80–150 words | What's the tension or problem? Specific enough to be real. |
| **The Core Idea** | 150–300 words | The actual thing Matt is saying. Use the framework, the story, the pattern. |
| **The Implication** | 80–120 words | What does this mean for someone reading it on a Tuesday morning? |
| **The One Thing** | 40–60 words | One question to sit with, or one action to take. Not both. |
| **Signoff** | 20–30 words | Matt's voice. Personal. Not a template. |

---

## Claude Instructions

Load all three foundation files before drafting.

### Step 1 — Confirm the through-line
State the one-sentence through-line before writing anything. If it isn't clear from the input, stop and ask.

### Step 2 — Draft each section
Write each section to its word target. Flag if you go over.

### Step 3 — Apply the creator-style rules
After drafting, run a style check:
- Check vocabulary against `creator-style.md`
- Check sentence rhythm
- Check the opening — does it work without context?
- Check the ending — is it one thing?

### Step 4 — Subject line options
Generate 4 subject line options:
- One: clear and direct
- One: curiosity-based (without being clickbait)
- One: challenge/provocation
- One: personal/specific

### Step 5 — Preview text
Write 1–2 sentences of preview text (what subscribers see below the subject line before opening). Must work with every subject line option.

---

## Output Template

```
## Newsletter Draft
Issue through-line: [One sentence]
Issue type: [Type]
Estimated word count: [N]

---

### Subject line options
1. [Direct]
2. [Curiosity]
3. [Challenge]
4. [Personal]

### Preview text
[1–2 sentences]

---

### Full Issue

**[Opening]**
[40–80 words]

**[Setup]**
[80–150 words]

**[Core Idea]**
[150–300 words]

**[Implication]**
[80–120 words]

**[The One Thing]**
[40–60 words]

**[Signoff]**
[20–30 words]

---

### Style check results
Vocabulary: Pass / Flag — [notes]
Rhythm: Pass / Flag — [notes]
Opening: Pass / Flag — [notes]
Ending: Pass / Flag — [notes]

### One thing to strengthen before sending:
[Specific note]
```

---

*Feeds into: monthly-review.md (tracking what issues resonated and why)*
