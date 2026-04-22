# Bettermode Q1–Q2 2026 — Task List

Tracks all work items from the [strategy doc](bettermode-strategy-2026.md). This repo is the source of truth — update Status as work moves.

---

## Phase 0 — Pre-Work (blockers: complete before publishing any content)

| # | Task | Owner | Status |
|---|------|-------|--------|
| 1 | ~~Pull Zendesk~~ Extracted from Matt's retention discovery (`docs/swim-lanes/retention/research/2026-03-26-support-data-findings.md`) | Kat | ✅ Done |
| 2 | ~~Pull data~~ Already in Brain: 56.2% of new Pros reach job 7 (11,685/20,796) — `docs/swim-lanes/retention/cold-start-blue/rating-rate-first-10.md` | Kat | ✅ Done |
| 3 | Pull Bettermode baseline: active Pro count + current post view rate | Kat | ✅ Done — `data/bettermode-baseline.md` |
| 3a | Resolve Zendesk reporting access — confirm whether Kat can get a direct reporting seat; if not, identify who currently holds access after seat holder changes (Nicole and Patrick may no longer have it) | Kat → Dustin + Seth | ⬜ Not started |

---

## Phase 1 — Focus Area 1: New Pro Success (First 60 Days)

### Space Setup

| # | Task | Notes | Status |
|---|------|-------|--------|
| 7a | Design the First 60 Days space in Bettermode Design Studio | Layout, branding, section structure — should feel distinct from the main community and immediately clear to a new Pro what this space is for | ⬜ Not started |
| 7b | Activate hidden Bettermode space for First 60 Days | Configure name, description, visibility — open to all members, framed for new Pros | ⬜ Not started |
| 7c | Write and pin space welcome post | Brief intro explaining what this space is and how to use it — not a content post, just orientation | ⬜ Not started |

### Distribution — Braze Trigger

| # | Task | Notes | Status |
|---|------|-------|--------|
| 7d | Confirm feasibility with Callie — can Braze trigger a follow-up text with the First 60 Days space link after a new Pro joins the community? | Need to know: (1) does Bettermode fire a joinable event Braze can listen to, and (2) can it be added to the existing new Pro journey without disrupting what's live | ⬜ Not started |
| 7e | If confirmed: implement Braze trigger — follow-up text with First 60 Days space link fires after new Pro joins community | Dependent on 7b (space must be live with a real link before this can be built) | ⬜ Not started |

### Content

| # | Task | Format | Priority | Status |
|---|------|--------|----------|--------|
| 7 | Publish: "Getting your first job — what to expect, how the queue works" | Short post + 1 action | P1 | ✅ Draft done — `drafts/task-07-getting-first-job.md` |
| 8 | Publish: "Your first service — photos, long grass, completing correctly" | Short post + 1 action | P1 | ✅ Draft done — `drafts/task-08-your-first-service.md` |
| 9 | Publish: "Understanding your tier score — what moves it, what doesn't" | Short post + 1 action | P1 | ✅ Draft done — `drafts/task-09-understanding-tier-score.md` |
| 10 | Publish: "Getting to Blue — what it means and how to get there" | Short post + 1 action | P1 | ✅ Draft done — `drafts/task-10-getting-to-blue.md` |

*Dependencies: Tasks 7a and 7b before publishing any content. Tasks 1 and 2 must be complete before publishing — baselines needed for measurement.*

---

## Phase 2 — Focus Area 2: Field Guide

| # | Task | Format | Priority | Status |
|---|------|--------|----------|--------|
| 11 | Write + publish: Long grass — how to report it, document it, why photos matter | Field guide post | P1 | ✅ Done — `drafts/task-11-long-grass.md` |
| 12 | Write + publish: When the customer cancels on you — what to do right now | Field guide post | P1 | ✅ Done — `drafts/task-12-customer-cancels.md` |
| 13 | Write + publish: Unresponsive customer — step by step | Field guide post | P1 | ✅ Done — `drafts/task-13-unresponsive-customer.md` |
| 14 | Write + publish: Payment questions — timing, breakdowns, where to look | Field guide post | P2 | ✅ Done |
| 15 | Write + publish: What actually affects your completion rate | Field guide post | P2 | ✅ Done — `drafts/task-15-completion-rate.md` |
| 16 | Implement Zendesk reference doc: maps ticket type to Bettermode post link — requires Dustin and Seth to add and pin it in Zendesk; draft ready for their review at `drafts/zendesk-bettermode-reference.md` | Zendesk pinned doc | — | ⬜ Not started |

*Zendesk reference doc (`drafts/zendesk-bettermode-reference.md`) must be updated with live links each time a Field Guide post is published.*

---

## Phase 3 — Focus Area 3: Tier Clarity

| # | Task | Format | Priority | Status |
|---|------|--------|----------|--------|
| 17 | Write + pin: Tiers and rewards explainer | Pinned post | P1 | ✅ Done — `drafts/task-17-tiers-and-rewards.md` |
| 18 | Set up milestone recognition system: Blue attainment celebration posts (opt-in) | Process + template | P2 | ✅ Done — `drafts/task-18-blue-milestone-recognition.md` |
| 19 | Launch monthly "What's moving your score" Q&A thread (recurring, first instance) | Monthly thread | P2 | ✅ Done — `drafts/task-19-monthly-qa-thread.md` |

---

## Phase 4 — Measurement Setup

| # | Task | Notes | Status |
|---|------|-------|--------|
| 20 | Set up tracking: Zendesk ticket volume by category (monthly snapshot) | Tracking template done — `data/tracking-zendesk-monthly.md`. Blocked on task 3a (Zendesk access must be confirmed before this can run on a real cadence) | 🔄 Template done, access pending |
| 21 | Set up tracking: Bettermode views per post (weekly export) | Depends on Task 3 baseline | ✅ Done — `data/tracking-bettermode-weekly.md` |

---

## Phase 5 — Focus Area 4: AMA Series

### Confirm Participants

| # | Task | Notes | Status |
|---|------|-------|--------|
| 22 | Confirm Steve — brief on current community tensions, get approval on his intro draft | Prior live AMA gives instant credibility — reference it in the thread | ⬜ Not started |
| 23 | Confirm PE rep — brief on likely question types, get approval on her intro draft | Expected topics: metrics, Wishlist items, app flow gaps, job queue logic | ⬜ Not started |
| 24 | Identify + confirm marketing rep — brief on GBP/Google reviews topics, get approval on intro draft | Topics: Google Business Profile, asking for reviews, local SEO, off-platform reputation | ⬜ Not started |
| 25 | Confirm Pro peer participant — brief on likely questions, get approval on intro draft | First choice: Scott Culala (490 all-time replies, already acts as mentor organically); backup: Arely Elrod | ⬜ Not started |
| 25a | Confirm Callie and Vinicius (Gamification) — brief on support ticket pattern, get approval on their intro draft | Gamification questions currently bounce through Kat or Support before reaching them — this thread eliminates that routing | ⬜ Not started |

### Month 1 — PE rep (Product & Engineering)

| # | Task | Format | Status |
|---|------|--------|--------|
| 26 | Post PE rep AMA thread | Ask the Community — `drafts/ama-product-engineering.md` | ⬜ Not started |
| 27 | Compile PE rep Q&As into FAQ post | Pro Academy — title: "You Asked, We Answered — [Month] with PE rep" | ⬜ Not started |

### Month 2 — Pro Peer (Gold/Platinum)

| # | Task | Format | Status |
|---|------|--------|--------|
| 28 | Post Pro Peer AMA thread | Ask the Community — `drafts/ama-pro-peer.md` | ⬜ Not started |
| 29 | Compile Pro Peer Q&As into FAQ post | Pro Academy — title: "You Asked, They Answered — [Month] with [Pro], [Tier] Pro" | ⬜ Not started |

### Month 3 — Marketing Rep

| # | Task | Format | Status |
|---|------|--------|--------|
| 30 | Post Marketing AMA thread | Ask the Community — `drafts/ama-marketing.md` | ⬜ Not started |
| 31 | Compile Marketing Q&As into FAQ post | Pro Academy — title: "You Asked, We Answered — [Month] with [rep], Marketing" | ⬜ Not started |

### Month 4 — Steve (CEO)

| # | Task | Format | Status |
|---|------|--------|--------|
| 32 | Post Steve AMA thread | Ask the Community — `drafts/ama-steve-ceo.md` | ⬜ Not started |
| 33 | Compile Steve Q&As into FAQ post | Pro Academy — title: "You Asked, Steve Answered — [Month]" | ⬜ Not started |

### Month 5 — Callie + Vinicius (Gamification)

| # | Task | Format | Status |
|---|------|--------|--------|
| 34a | Post Gamification AMA thread | Ask the Community — `drafts/ama-gamification.md` | ⬜ Not started |
| 34b | Compile Gamification Q&As into FAQ post | Pro Academy — title: "You Asked, We Answered — [Month] with Callie and Vinicius, Gamification" | ⬜ Not started |

*Dependencies: Tasks 22–25a (confirmations) must be complete before their respective thread goes live. Each compile task follows its thread after 7–10 days or when activity slows.*

---

## Phase 6 — Focus Area 5: Pool Pro Space

### Discovery

| # | Task | Notes | Status |
|---|------|-------|--------|
| 34 | Meet with Trent M. — understand Pool Pro experience, pain points, questions | Trent is active in the main community (10 posts); first voice to consult before building anything | ⬜ Not started |
| 35 | Pull sentiment from Will and Shannon — what themes and complaints come up most on the Pool Pro Facebook page | Facebook page is LawnStarter-run but not connected to Bettermode; this is untapped signal | ⬜ Not started |
| 36 | Confirm with PE rep (PE): do pool Pro metrics work differently from lawn care Pro metrics? | Answer determines whether tier/metrics content needs to be written separately or can reuse existing posts | ⬜ Not started |
| 37 | Review hidden Bettermode space — confirm what needs to change to activate it for Pool Pros | Check space settings, visibility, membership rules in Bettermode admin | ⬜ Not started |
| 37a | Connect with Jeff Herman's team — inventory what Pool Pro content is available or in progress to feature in the space | Jeff's team is actively producing Pool Pro content; coordinate so the space surfaces their work rather than duplicating it | ⬜ Not started |

### Build (pending discovery)

| # | Task | Notes | Status |
|---|------|-------|--------|
| 38 | Activate and configure the Pool Pro space in Bettermode | Scope determined by tasks 34–37 | ⬜ Not started |
| 39 | Write initial Pool Pro content — topics TBD from discovery | At minimum: welcome post, one field guide equivalent, metrics/tier clarity if needed | ⬜ Not started |

*Dependencies: Tasks 34–37 must be complete before 38–39. Do not build before discovery is done.*

---

## Notes

- **"Draft done" ≠ published.** All content marked `Draft done` still needs to go through the full publishing workflow before it goes live. See `drafts/content-publishing-workflow.md` for all 8 steps: fact check → tone pass (AI tool) → Bettermode formatting → 7-day org review → edits → asset creation (if needed) → publish.
- **Phase 1 space setup (7a–7c) must come before publishing any First 60 Days content (7–10).** Design the space first, then activate, then publish.
- **Braze trigger (7d–7e)** is a dependency on Callie — confirm feasibility before building anything.
- **Field Guide posts (11–15)** are drafted and ready. Update the Zendesk reference doc (`drafts/zendesk-bettermode-reference.md`) with the live link each time one is published.
- **AMA confirmations (22–25)** gate their respective threads — nothing goes live without the participant's approval on their intro draft.
- **Pool Pro space (34–39)** is discovery-first — do not build before tasks 34–37 are complete.
- After any content is published: update `data/bettermode-content-tracker.md` with the live link and status.
- Update the Status column as tasks move: ⬜ Not started → 🔄 In progress → ✅ Draft done → ✅ Published
