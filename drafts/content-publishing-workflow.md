# Content Publishing Workflow
Applies to: all Bettermode content (Pro Academy posts, Field Guide, First 60 Days, AMA FAQ compilations)
Owner: Kat Kennedy

Every piece of content goes through these steps before it's published. "Draft done" means step 1 only.

---

## Steps

### Step 1 — Draft
Write the initial draft. For most content this happens in Claude/AI or directly in the drafts folder in this repo.

**Status label:** `Draft done`

---

### Step 2 — Fact Check
Review the draft for accuracy against:
- Current app behavior and flows
- Correct tier/metric definitions
- Accurate payout and payment details
- Any KB or support documentation that covers the same topic

Flag anything that needs confirmation from PE, Support, or Ops before moving forward.

**Status label:** `Fact checking`

---

### Step 3 — Tone Pass (AI Tool)
Run the fact-checked draft through the AI writing tool to match Kat's voice and the community's tone. The goal is to sound like a person, not a help center article.

**Status label:** `Tone pass`

---

### Step 4 — Bettermode Formatting
Format the post for Bettermode:
- Apply correct heading structure
- Break up walls of text
- Add any callouts, bullets, or visual breaks that fit the post type
- Confirm the post type (Pro Academy article vs. thread vs. pinned post)
- Note if an image or video is needed (see Step 7)

**Status label:** `Formatting`

---

### Step 5 — Org Review (7 Days)
Share the formatted draft with relevant teammates for review. Open review window = 7 days.

Who to loop in depends on the content:
- **Field Guide posts** — Support manager (confirm accuracy of flows and ticket language)
- **Tier/metrics content** — PE rep (confirm metric logic is correct)
- **Earning/pricing content** — Ops or account management
- **AMA FAQ compilations** — The AMA participant (confirm their answers are quoted correctly)

Collect feedback. Only incorporate changes that are accurate or meaningfully improve the post.

**Status label:** `In review`

---

### Step 6 — Edits
Make revisions based on review feedback where relevant. Not all feedback requires a change — use judgment.

**Status label:** `Edits`

---

### Step 7 — Asset Creation (if needed)
Some posts need a visual before publishing:
- **Image** — custom graphic, screenshot, or branded visual
- **Video** — training video or screen recording (coordinate with whoever produces video)

Not every post needs this. Flag at Step 4 if an asset is needed so it doesn't hold up publishing.

**Status label:** `Asset creation`

---

### Step 8 — Draft into Bettermode + Publish
Build the post in Bettermode, apply final formatting, attach any assets, and publish.

After publishing:
- Add the live link to `data/bettermode-content-tracker.md`
- Update the Zendesk reference doc (`drafts/zendesk-bettermode-reference.md`) if the post maps to a support ticket type
- Update task status in `task-list.md` to `Published`

**Status label:** `Published`

---

## Status Labels (for task-list.md)

| Label | Meaning |
|-------|---------|
| `Draft done` | Step 1 complete — draft exists in repo |
| `Fact checking` | Step 2 in progress |
| `Tone pass` | Step 3 in progress |
| `Formatting` | Step 4 in progress |
| `In review` | Step 5 — open for org review, 7-day window |
| `Edits` | Step 6 — incorporating feedback |
| `Asset creation` | Step 7 — image or video being produced |
| `Published` | Step 8 complete — live on Bettermode |

---

## Notes

- Steps 2–4 can be done in sequence by Kat without waiting on anyone
- Step 5 (org review) is the only step with an external dependency and a time window — start it early enough that it doesn't delay the publish date
- Steps can overlap slightly (e.g., formatting while waiting on a fact-check response) but don't skip
- Asset creation (Step 7) should be flagged at Step 4 so production can happen in parallel with org review

---

## Content Status Tracker

### First 60 Days Series

| Post | File | Status |
|------|------|--------|
| Post 1 of 4 — Getting Your First Job: What to Expect | `drafts/task-07-getting-first-job.md` | `Draft done` |
| Post 2 of 4 — Your First Service: Photos, Long Grass, Completing Correctly | `drafts/task-08-your-first-service.md` | `Draft done` |
| Post 3 of 4 — Understanding Your Tier Score: What Moves It, What Doesn't | `drafts/task-09-understanding-tier-score.md` | `Draft done` |
| Post 4 of 4 — Getting to Blue: What It Means and How to Get There | `drafts/task-10-getting-to-blue.md` | `Draft done` |
