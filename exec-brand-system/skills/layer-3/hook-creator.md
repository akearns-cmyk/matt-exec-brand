# Hook Creator — Layer 3 Skill

> **Purpose:** Take a developed insight and generate opening lines that earn the click, the scroll, and the read.
> A hook is not a trick. It is a promise the content must keep.
>
> **Depends on:** `foundation/point-of-view.md`, `foundation/creator-style.md`, `foundation/audience-delight.md`
> **Typically follows:** `skills/layer-2/insight-extractor.md`

---

## When to Use This

- You have a clear insight (from the extractor or Matt's own clarity) and need a strong opening
- Matt is rewriting a draft that starts too slowly
- You need 5+ options to pick from before committing to a direction

---

## Input Format

**The core insight in one sentence:**
```
[PASTE THE CLAIM HERE]
```

**Target platform:** LinkedIn / Newsletter / Talk Abstract

**Any constraints:** [e.g., "Can't reference a specific client," "This is for a more technical audience," "Keep it under 200 characters for the first line"]

---

## Claude Instructions

Load `foundation/creator-style.md` before generating hooks. All hooks must pass the style rules in that file.

### Generate hooks in each of these 6 categories:

---

**1. The Counterintuitive Statement**
Opens by saying the opposite of what they expect.
> Format: "[Common belief] is wrong. / The real problem is [X]."
> Rule: Must be provably true, not just edgy.

---

**2. The Specific Observation**
Opens with something Matt has actually seen — no abstraction.
> Format: "I've watched [specific thing happen] in [specific context] more times than I can count."
> Rule: The specificity is the hook. No generalizations.

---

**3. The Named Pattern**
Opens by giving a name to something the reader already experiences but hasn't labeled.
> Format: "There's a thing I call [name]. You've seen it. Here's what it actually is."
> Rule: The name must be useful, not cute.

---

**4. The Honest Admission**
Opens with something that costs Matt something to say.
> Format: "I used to [believe/do X]. I was wrong."
> Rule: The admission must be real. Fake vulnerability is immediately detectable.

---

**5. The Stakes Statement**
Opens with why it matters — right now, for this audience.
> Format: "If you're [in this situation], what I'm about to say is worth stopping for."
> Rule: Earned, not manufactured urgency.

---

**6. The Scene**
Opens in the middle of a real moment.
> Format: "[Present tense scene]. That's when I understood [X]."
> Rule: The scene must be specific enough to be cinematic. Generic scenes don't work.

---

### After generating hooks:

**Rate each hook** on two dimensions (1–5):
- **Authenticity:** Does this sound like Matt or like "LinkedIn voice"?
- **Pull:** Would someone who has already heard a thousand posts stop for this one?

**Recommend the top 2** with a one-sentence explanation of why.

**Flag any** that violate rules in `creator-style.md`.

---

## Output Template

```
## Hooks for: [Insight title]
Platform: [Platform]

### 1. Counterintuitive Statement
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

### 2. Specific Observation
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

### 3. Named Pattern
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

### 4. Honest Admission
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

### 5. Stakes Statement
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

### 6. Scene
> [Hook text]
Authenticity: [1-5] | Pull: [1-5]

---

## Recommended: #[N] and #[N]
[Reason for each]

## Style flags (if any):
[Any hooks that violated creator-style.md rules]
```

---

*Feeds into: linkedin-drafter.md, newsletter-writer.md, post-enricher.md*
