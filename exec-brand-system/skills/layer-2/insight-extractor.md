# Insight Extractor — Layer 2 Skill

> **Purpose:** Take raw material (a conversation, meeting notes, a shower thought, a rant, a voice memo transcript) and extract the ideas worth developing.
> This skill does NOT write content. It surfaces what's worth writing about.
>
> **Depends on:** `foundation/point-of-view.md`, `foundation/audience-delight.md`

---

## When to Use This

- Matt has a raw dump of thoughts and doesn't know what to do with them
- After a notable meeting, client call, or hard conversation
- When something has been bothering him and he can't name why
- When he's seen a pattern repeat enough times to be worth naming

---

## Input Format

Paste the raw material below. It can be:
- Bullet points
- A voice memo transcript
- A brain dump paragraph
- A slack message he wrote but never sent
- A conversation summary
- A link to an article that triggered a reaction

**Raw material:**
```
[PASTE RAW INPUT HERE]
```

---

## Claude Instructions

When this skill is invoked, Claude should:

### Step 1 — Read the foundations
Load `foundation/point-of-view.md` and `foundation/audience-delight.md` before analysis.

### Step 2 — Extract candidates
Identify 3–5 distinct ideas embedded in the raw material. For each one, produce:

**Idea [N]: [Working title — sharp, not clever]**
- **The core claim:** One sentence. What is Matt actually saying?
- **Why it's interesting:** Does it challenge an assumption? Name a pattern? Offer a new frame?
- **POV pillar it connects to:** Which pillar from `point-of-view.md` does this reinforce or extend?
- **Audience resonance:** Which fear or hunger from `audience-delight.md` does this address?
- **Raw material quotation:** The 1–2 sentences from the input that contain the seed of this idea
- **Development potential:** High / Medium / Low — and why

### Step 3 — Flag conflicts
Note any ideas that feel off-brand, contradict established POV pillars, or seem like they belong to a different voice.

### Step 4 — Recommend
Pick ONE idea to develop first. State why — be specific about the intersection of:
- POV fit
- Audience timing (is this something they need right now?)
- Matt's ability to tell it with specificity (does he have a real story or example?)

### Step 5 — Ask one question
Ask Matt the single question that, if answered, would unlock the best version of the recommended idea.

---

## Output Template

```
## Extracted Insights

### Idea 1: [Title]
Core claim: ...
Why interesting: ...
POV pillar: ...
Audience resonance: ...
Source quote: "..."
Development potential: High/Medium/Low — [reason]

### Idea 2: [Title]
...

### Idea 3: [Title]
...

---

## Recommendation
Develop **[Idea N]** first because...

## The Unlocking Question
Before writing, answer this: ...
```

---

*Feeds into: hook-creator.md, post-enricher.md, linkedin-drafter.md, newsletter-writer.md, talk-abstract.md*
