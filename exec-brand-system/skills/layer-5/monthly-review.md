# Monthly Review — Layer 5 Skill

> **Purpose:** Run a structured monthly retrospective on content performance, POV evolution, and what to build next.
> This is the system's feedback loop. Without it, the brand drifts.
>
> **Depends on:** All foundation files, all Layer 4 outputs from the month
> **Runs:** Once per month (suggested: first Monday of the month)

---

## When to Use This

- End of each month — before planning the next month's content
- When something performed surprisingly well or poorly and Matt wants to understand why
- When the brand feels like it's lost its thread
- When deciding whether to update a foundation file

---

## Input Format

**Month being reviewed:** [e.g., "May 2026"]

**LinkedIn posts published this month:**
```
Paste titles or first lines, with any engagement notes you have.
1.
2.
3.
...
```

**Newsletter issues sent:**
```
Subject lines + any open rate / reply data if available
1.
2.
```

**Talk abstracts submitted or talks given:**
```
Event name, status (submitted / accepted / delivered)
1.
2.
```

**Content that surprised you (positive or negative):**
```
[What performed above or below expectation, and your gut reaction to why]
```

**One thing you're thinking about that didn't become content yet:**
```
[The idea in the drawer — what is it?]
```

---

## Claude Instructions

Load all three foundation files before running the review.

---

### Section 1 — Performance Audit

For each piece of content listed:

| Content | Platform | POV Pillar | Audience Resonance | Performance Signal | Hypothesis for Why |
|---|---|---|---|---|---|
| [Title] | [Platform] | [Pillar #] | [Fear/Hunger addressed] | [High/Med/Low or data] | [1-sentence theory] |

After the table:
- **What pattern emerges?** Which pillar, audience fear, or format drove the most resonance?
- **What underperformed?** Be specific about what the data suggests, not just what "could have been better."

---

### Section 2 — Voice & POV Drift Check

Answer these questions honestly:

1. **Did any content this month feel like it was written for the algorithm rather than the audience?**
   [Yes / No / Which ones]

2. **Did Matt say anything this month that surprised even him — where the writing clarified his own thinking?**
   [What was it? This is often where a POV pillar is evolving.]

3. **Is any content from this month inconsistent with the POV pillars in `foundation/point-of-view.md`?**
   [Yes / No — if yes, is it a drift to correct or a signal that the pillar should update?]

4. **Did the voice stay consistent with `foundation/creator-style.md`?**
   [Yes / No — note any drift patterns]

---

### Section 3 — Foundation File Update Candidates

Based on the month's work, evaluate whether any foundation file needs updating:

**`point-of-view.md` — Update needed?**
[ ] No — pillars still accurate
[ ] Yes — [which pillar, and what changed]
[ ] New pillar to add — [describe it]
[ ] Pillar to retire or merge — [which one and why]

**`audience-delight.md` — Update needed?**
[ ] No — still accurate
[ ] Yes — [what changed about the audience understanding]
[ ] New fear or hunger surfaced — [describe]
[ ] Something the audience was allergic to that we didn't have listed — [what]

**`creator-style.md` — Update needed?**
[ ] No — still accurate
[ ] Yes — [what should be added, removed, or adjusted]
[ ] A new structural pattern that worked well — [describe so it can be added]
[ ] A construction that felt wrong in practice — [describe so it can be added to forbidden list]

---

### Section 4 — The Idea in the Drawer

For the idea Matt listed as undeveloped:

1. **Why hasn't it become content?** (Choose one)
   - The idea isn't developed enough yet
   - No clear platform fit
   - It feels risky or uncertain
   - Matt isn't sure it fits his POV
   - It needs more evidence or examples
   - Other: ___________

2. **What would need to be true for this to become content?**
   [Specific answer — not "more clarity" but what specific thing would unlock it]

3. **Recommended next action:**
   [ ] Run through `insight-extractor.md` now
   [ ] Let it marinate — check again next month
   [ ] It's not a content idea — it belongs somewhere else (where?)
   [ ] Abandon it — here's why: ___________

---

### Section 5 — Next Month's Content Plan

Based on everything above, recommend:

**2–3 LinkedIn posts to prioritize:**
1. [Insight + recommended hook type from hook-creator.md]
2. [Insight + recommended hook type]
3. [Insight + recommended hook type]

**1 newsletter issue:**
[Through-line + why now]

**Any talk submissions to pursue:**
[Event + talk angle + why this month]

**One new thing to try:**
[A format, angle, or approach Matt hasn't tested yet — specific and small]

---

## Output Template

```
## Monthly Review — [Month Year]

### Section 1 — Performance Audit
[Table]

Pattern that emerges: ...
What underperformed: ...

---

### Section 2 — Voice & POV Drift Check
1. Algorithm drift: ...
2. Surprising clarity: ...
3. POV inconsistency: ...
4. Voice consistency: ...

---

### Section 3 — Foundation File Updates
point-of-view.md: [No update / Update: ...]
audience-delight.md: [No update / Update: ...]
creator-style.md: [No update / Update: ...]

---

### Section 4 — The Idea in the Drawer
Idea: [Name it]
Why it hasn't happened: ...
What would unlock it: ...
Recommended action: ...

---

### Section 5 — Next Month's Plan
LinkedIn posts:
1. ...
2. ...
3. ...

Newsletter: ...

Talk submissions: ...

One new thing to try: ...
```

---

*This skill is the only one that writes back to the foundation files (via recommendations).*
*Act on Section 3 updates before the next month begins.*
