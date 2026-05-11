# Post Enricher / Authenticity Layer — Layer 3 Skill

> **Purpose:** Take a draft and run it through three lenses — Human Rewrite, Pattern Disruptor, and Voice Shaper.
> This is where "good draft" becomes "unmistakably Matt."
>
> **Depends on:** `foundation/creator-style.md`, `foundation/point-of-view.md`, `foundation/audience-delight.md`
> **Typically follows:** `hook-creator.md` or after a first draft from any Layer 4 skill

---

## When to Use This

- A draft exists but feels generic, safe, or like it could have been written by anyone
- Matt has written something but it doesn't feel like *him*
- A LinkedIn post, newsletter section, or talk excerpt needs its last pass before publishing
- You want a diagnostic before hitting publish

---

## Input Format

**Draft to enrich:**
```
[PASTE DRAFT HERE]
```

**What type of content is this?**
[ ] LinkedIn post
[ ] Newsletter section
[ ] Talk excerpt
[ ] Other: ___________

**What's the main concern with the draft?**
[ ] Too generic
[ ] Too safe / hedge-y
[ ] Sounds like AI or corporate voice
[ ] Right ideas, wrong structure
[ ] Correct but not interesting
[ ] Other: ___________

---

## The Three Lenses

Run the draft through each lens in order. Each lens produces a rewrite, not just notes.

---

### Lens 1 — Human Rewrite

**Question this lens asks:** "Would a real person say this?"

**What it fixes:**
- Passive constructions masquerading as insight
- Phrases that exist nowhere in actual human speech
- Conclusions that are too tidy — real wisdom has friction
- Anything that sounds like it was optimized for a content algorithm

**Instructions for Claude:**
1. Read the draft aloud (mentally). Flag every phrase that sounds like it was written, not said.
2. Rewrite the flagged sections using natural speech patterns — the way Matt would say this in a conversation, not a presentation.
3. Preserve the logic. Change the texture.
4. Do not make it informal if Matt isn't informal. Make it *real*.

**Output:** Full rewritten draft + a bulleted list of what changed and why.

---

### Lens 2 — Pattern Disruptor

**Question this lens asks:** "Have I seen this post before?"

**What it fixes:**
- Structural clichés (e.g., "Here are 5 lessons I learned from X")
- Predictable endings ("So the question is: what will YOU do?")
- The "vulnerability sandwich" (humble opener → insight → humble closer)
- Ideas that are true but familiar — needs a new angle of attack

**Instructions for Claude:**
1. Identify the structural pattern the draft is using.
2. Name it explicitly: "This is a [List post / Confession arc / Hero's journey / Problem-solution / Before-after]."
3. Generate ONE alternative structure that serves the same insight differently.
4. Rewrite the draft in that alternative structure.
5. Mark which version is stronger and why — don't hedge.

**Output:** Named pattern + alternative structure + rewritten draft + recommendation.

---

### Lens 3 — Voice Shaper

**Question this lens asks:** "Does this sound like Matt, specifically?"

**What it fixes:**
- Vocabulary drift (words Matt wouldn't use)
- Rhythm drift (sentences that don't match his cadence)
- Tone drift (more formal or more casual than his range)
- Missing fingerprints — the sentence constructions and moves that are distinctly his

**Instructions for Claude:**
1. Load `foundation/creator-style.md`.
2. Audit the draft against:
   - Vocabulary (flag any words on the avoid list; flag any missing words from his typical vocabulary)
   - Sentence rhythm (check against the structural patterns he uses)
   - Forbidden constructions (check the explicit list)
3. Rewrite any sections that fail the audit.
4. Add one "fingerprint moment" if the draft doesn't have one — a sentence that could only come from Matt's specific POV.

**Output:** Audit results (pass/fail per category) + final polished draft with voice corrections.

---

## Final Synthesis

After running all three lenses, produce:

**The Publish-Ready Draft**
The best version — may draw from any of the three lens rewrites, or synthesize across them.

**Confidence Score:** [1–10] — How confident are you this sounds like Matt and will land with his audience?

**The One Thing Left to Add:**
Is there a specific detail, story beat, or sentence that would make this 20% stronger? Name it exactly.

---

## Output Template

```
## Post Enricher Results
Content type: [Type]
Primary concern addressed: [Concern]

---

### Lens 1 — Human Rewrite
Changes made:
- [Change + reason]
- [Change + reason]

Rewritten draft:
[DRAFT]

---

### Lens 2 — Pattern Disruptor
Original structure: [Name]
Alternative structure: [Name + brief description]

Rewritten draft:
[DRAFT]

Recommendation: [Which version and why]

---

### Lens 3 — Voice Shaper
Vocabulary audit: Pass / Fail — [notes]
Rhythm audit: Pass / Fail — [notes]
Forbidden constructions: Pass / Fail — [notes]
Fingerprint added: [Y/N — what it is]

Rewritten draft:
[DRAFT]

---

### Publish-Ready Draft
[FINAL VERSION]

Confidence score: [1-10]

The one thing left to add: [Specific suggestion]
```

---

*This is the last stop before a Layer 4 skill produces the final formatted output.*
*Feeds into: linkedin-drafter.md, newsletter-writer.md, talk-abstract.md*
