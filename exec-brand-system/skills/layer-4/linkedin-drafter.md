# LinkedIn Drafter — Layer 4 Skill

> **Purpose:** Produce a publish-ready LinkedIn post from a polished insight and hook.
> This skill handles LinkedIn-specific formatting, pacing, and CTA — not ideation.
>
> **Depends on:** `foundation/creator-style.md`, `foundation/audience-delight.md`, `foundation/point-of-view.md`
> **Typically follows:** `hook-creator.md` and/or `post-enricher.md`

---

## When to Use This

- You have a chosen hook and enriched draft and need the final LinkedIn format
- Matt wants to post something specific and needs it shaped for the platform
- You're batching posts for the week and need to produce multiple outputs quickly

---

## Input Format

**The core insight:**
```
[One sentence]
```

**Chosen hook (from hook-creator.md or Matt's own):**
```
[First line of the post]
```

**Draft content or key points to include:**
```
[Can be bullet points, a rough draft, or a structured note]
```

**Post type:**
[ ] Observation / insight
[ ] Story with lesson
[ ] Framework / named concept
[ ] Honest reflection
[ ] Industry take / contrarian view
[ ] Announcement (use sparingly)

**Desired length:**
[ ] Short (150–250 words)
[ ] Medium (300–450 words)
[ ] Long (500–700 words — for high-value frameworks only)

---

## LinkedIn Format Rules

Load `foundation/creator-style.md` before drafting. Then apply these platform-specific rules:

### Structure
1. **Line 1:** The hook. Must work before "...see more" cutoff.
2. **Line 2:** [blank line]
3. **Body:** Develops the insight. Short paragraphs. Maximum 3 lines each.
4. **Transition:** One line that pivots to the implication or the so-what.
5. **Close:** One thing — either a question, an action, or a landing statement. Not all three.

### Formatting Rules
- No headers (##, bold headers) inside the post
- No bullet lists in the first 3 paragraphs
- If using a list, max 5 items, each one specific and non-obvious
- Em dashes and periods only — no exclamation points
- Numbers are fine if they're real (not "5 ways to...")
- Hashtags: 0–3, at the very end, only if they're genuinely useful categories

### LinkedIn-Specific Prohibitions
- Do not open with "I" as the first word (algorithmic penalty + weak opener)
- Do not use "Thoughts?" as the CTA — it's a signal of low-effort content
- Do not end with a list of 3 rhetorical questions
- Do not write "This is so important" or "This changed everything"
- Do not use "swipe left" or references to carousel mechanics in text posts

---

## Claude Instructions

### Draft the post in two versions:

**Version A:** Tighter. Cuts anything that doesn't earn its place. Trusts the reader.

**Version B:** Fuller. Uses one more example or scene to make the idea land for someone less familiar with the context.

### Then:
- Flag any lines that violate `creator-style.md` rules
- Score each version: Authenticity [1–5] / Clarity [1–5] / Likely to perform [1–5]
- Recommend one version, with one specific edit that would make it stronger

---

## Output Template

```
## LinkedIn Draft
Insight: [One sentence]
Post type: [Type]
Target length: [Length]

---

### Version A (Tighter)

[FULL POST TEXT]

---

### Version B (Fuller)

[FULL POST TEXT]

---

### Scores
|              | Authenticity | Clarity | Likely to perform |
|--------------|:---:|:---:|:---:|
| Version A    | /5  | /5  | /5  |
| Version B    | /5  | /5  | /5  |

### Recommendation
Version [A/B] — because [specific reason].

### One edit that would make it stronger:
[Specific line or addition]

### Style flags (if any):
[Lines that violated creator-style.md]
```

---

## Posting Cadence Guidance

*(Not enforced by this skill, but provided for planning context)*

| Post type | Frequency |
|---|---|
| Insight / observation | 2–3x per week |
| Story with lesson | 1x per week |
| Framework / named concept | 1–2x per month |
| Honest reflection | 1x per month |
| Contrarian take | 1x per month |
| Announcement | Only when newsworthy |

---

*Feeds into: post-enricher.md (if another pass is needed), monthly-review.md (for performance tracking)*
