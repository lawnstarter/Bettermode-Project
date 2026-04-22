# Bettermode Strategy: Q1–Q2 2026
**Owner:** Katherine Kennedy
**Due:** End of week (April 25, 2026)
**For:** Matt

---

## What This Is

A data-backed plan for how Bettermode should operate over the next quarter. Not a content calendar. Not a list of ideas. Three focus areas chosen because the data says they move the needle — with defined outcomes and a way to measure each one.

---

## The Lens

> *"What problems are Pros bringing to us that we can solve through Bettermode?"*

Every piece of content, every post, every thread in Bettermode should trace back to a real problem with a real cost. If I can't answer "what does success look like?" — I don't do it.

---

## Focus Area 1: New Pro Success (Days 1–60)

### The Problem

Half of new Pros never reach job 10. Of the 20,796 Pros who completed their first job in 2024–2025, only 10,217 made it to job 10. We're losing them before the tier system even has a chance to sort them.

The window that matters is **jobs 1–7**. That's when ~3 ratings accumulate — the point where our data can cleanly separate Pros who will reach Blue from those who won't (7.7× separation between the top and bottom rating buckets). If we don't reach new Pros before job 7, we miss the intervention window entirely.

### What New Pros Are Actually Asking

Based on the onboarding FAQ and support ticket data, the top questions in the first 60 days are:

1. When will I get my first job?
2. How do I get more jobs / what affects how many I receive?
3. How does pay work (timing, breakdowns)?
4. What do I do when something goes wrong at a property?
5. How does my tier score work — what hurts it, what helps it?

None of these are exotic. They're predictable. We know them already. The gap is that Pros have to find the answers themselves — in a help center, through support, or by trial and error.

### What I'll Build in Bettermode

**A structured "First 60 Days" content series** — not a formal course, not a drip campaign. A living set of pinned posts and threads that answer the questions new Pros have at the moment they have them.

| Week | Topic | Tied to |
|------|-------|---------|
| Week 1–2 | Getting your first job: what to expect, how the queue works | New Pro drop-off before job 1 |
| Week 2–3 | Your first service: photos, long grass, completing correctly | First-job cancellation risk (customers 50% more likely to cancel if first service misses) |
| Week 3–5 | Understanding your tier score: what moves it, what doesn't | Rating/tier confusion is the #3 support ticket type |
| Week 5–7 | Getting to Blue: what Blue actually means and how to get there | 65% of Pros with ≥4.8 avg at 3 ratings reach Blue — this is achievable and they should know it |

**Format:** Short posts with a clear answer + one action. No walls of text. Visual where possible.

**Home:** A dedicated Bettermode space — activated from an existing hidden space — so new Pros have one place to go rather than hunting through Ask the Community. All four posts live here, pinned and ordered. The space is visible to all members but clearly framed for new Pros.

### Distribution — Getting New Pros Into the Space

The space has no value if new Pros don't find it. The existing Braze flow already texts new Pros an invitation to join the community (sent by Callie). The goal is to add a follow-up text that sends the First 60 Days space link automatically after they join.

This requires confirming two things:
1. Does Bettermode fire an event (webhook or API signal) when a user joins that Braze can listen to?
2. If so, can a triggered message be added to the existing new Pro Braze journey without disrupting what's already live?

If the trigger is possible, this becomes the primary distribution mechanism — no manual work, no hoping new Pros find it themselves.

### Who Should Be Involved

- **Callie** — owns the Braze new Pro journey; confirm whether the trigger is technically possible and whether it fits the existing flow
- **Support team** (consult): Pull the actual top tickets from new Pros in their first 60 days. I want the real questions, not my guess at them. One-time data pull, no ongoing involvement needed.

### Expected Outcome

New Pros who engage with this content understand the tier system and what to do on their first few jobs before they hit a wall. The direct signal: fewer support tickets from new Pros on tier/rating questions; more Pros completing job 7+.

### How I'll Measure It

| Metric | Baseline | Target |
|--------|----------|--------|
| Support ticket volume: rating/tier questions from Pros < 60 days | TBD (pull from Zendesk) | -20% within 90 days |
| Bettermode engagement on new-Pro content | 0 (new) | 15%+ of active new Pros view at least one post |
| New Pro completion rate at job 7 | TBD (pull from data) | Hold or improve vs. current cohort |

---

## Focus Area 2: High-Frequency Problem Scenarios

### The Problem

Problem scenarios affect **nearly 40% of schedules**. When they happen, customers have a 15% lower retention rate than when they don't. For first-job customers, the cancel rate after a service issue is 43.3%.

The top support tickets Pros send are entirely predictable:

1. Payment/payout disputes ("I completed the job and didn't get paid")
2. Customer cancellation requests ("Customer told me personally she wants to cancel")
3. Rating and tier confusion ("Why does that count against my score?")
4. Unresponsive customer ("I tried to contact the customer, no response")
5. Long grass disputes (68% of long grass disputes claim the grass wasn't over 9 inches — this is a **pricing trust problem**, not a service quality problem)

These aren't random. They happen constantly. And Pros currently have no proactive resource explaining how to navigate them.

### What I'll Build in Bettermode

**A "Field Guide" content library** — one post per high-frequency scenario, written from the Pro's perspective, covering exactly what to do and why.

Priority topics (in order):

1. **Long grass: how to report it, how to document it, and why photos matter** — This directly addresses the 68% dispute rate where customers challenge the fee. A Pro who knows to document with timestamped photos before completing is much harder to dispute.
2. **When the customer cancels on you** — Pros currently have no app option for this. The content should explain what to do in the app right now (pause report + contact support), why property-dropping hurts their metrics, and what's coming.
3. **Unresponsive customer: what to do step by step** — Covers the reporting flow, GPS ping requirement for trip fees, and how to protect their score.
4. **Payment questions: what to expect and where to look** — Payment timing and the payout breakdown screen are the #1 new Pro question and easily answered.
5. **What actually affects your completion rate** — Clarifies what counts, what doesn't, and the buffer that already exists in the metrics.

### Who Should Be Involved

- **No one for content creation.** I can write these from existing KB articles and the problem flows research.
- **Support team** (inform only): Alert them when posts go live so they can link to them in tickets. Reduces their handle time too.

### Expected Outcome

Pros who encounter a problem scenario know what to do without calling support. The direct signal: support ticket volume drops for these specific issue types.

### How I'll Measure It

| Metric | Baseline | Target |
|--------|----------|--------|
| Support tickets: long grass disputes | TBD | -15% within 60 days of content going live |
| Support tickets: unresponsive customer / customer cancellation | TBD | -20% within 60 days |
| Bettermode views on Field Guide posts | 0 (new) | Track weekly; at least 25 unique views per post within 30 days |

---

## Focus Area 3: Tier System Clarity

### The Problem

Rating and tier confusion is the **#3 reason Pros contact support.** It also drives a behavioral problem: lower-tier Pros avoid reporting issues honestly because they're afraid of hurting their metrics. This means the Pros who most need guidance are the ones most likely to game around the system rather than work with it.

The data also shows a "coachable middle" that Bettermode can reach. Pros with a 4.00–4.49 average rating at 3 jobs have a 35% chance of reaching Blue — but that jumps to 63% by job 10. There's real lift available if we can help these Pros understand what's holding them back and what to fix.

### What I'll Build in Bettermode

**A Tier Clarity content track** — not a one-time post, a recurring reference.

1. **"How the tier system actually works"** — A plain-language explainer pinned in the community. Covers: what Blue/Intro/Red mean for new Pros, how review surplus works (not the same as average rating), what completion rate counts and what it doesn't, and the one thing that matters most in the first 10 jobs (getting reviews and keeping them above 4.5).
2. **Milestone recognition posts** — When a Pro reaches Blue, I post a congratulation in the community (opt-in). Public recognition of the milestone makes the path feel real and achievable to Pros who are still Intro/Red.
3. **Monthly "What's moving your score" thread** — A structured Q&A thread where Pros can ask specific questions about their metrics. I answer from the reference data. This replaces random venting with structured, useful signal.

### Who Should Be Involved

- **Nobody externally.** This is content I own and can produce from existing documentation.
- **Ops/account management** (inform): If Pros start tagging specific metric questions I can't answer, I'll route to them. But they don't need to be in the room for content creation.

### Expected Outcome

Pros understand their tier score well enough to work with it rather than around it. Lower-tier Pros feel less defensive and more like the system is navigable. The coachable-middle cohort has a higher rate of Blue attainment.

### How I'll Measure It

| Metric | Baseline | Target |
|--------|----------|--------|
| Support tickets: rating/tier confusion | TBD | -20% within 90 days |
| Blue attainment rate: 4.00–4.49 bucket at 3 ratings | ~35% currently | Track vs. new-Pro cohorts exposed to content |
| Bettermode engagement on tier content | 0 (new) | 20%+ of community members view at least one tier post/month |

---

## Focus Area 4: Expert Access Rotation (AMA Series)

### The Problem

Admin accounts for 32% of all community activity (2,170 of 6,760 total activities). HQ is doing a disproportionate share of engagement. The community's most discussed topics — metrics confusion, off-platform growth, pricing frustration — need voices beyond Katherine to resolve. Pros already know she'll answer. What builds deeper trust is when they can get straight answers from the people making decisions and from Pros who've already figured things out.

### What I'll Build in Bettermode

An **async AMA rotation** — one standing thread per month in Ask the Community, answered by a different expert over 7–10 days, then compiled into a searchable FAQ post in Pro Academy.

| Month | Participant | Theme |
|-------|-------------|-------|
| 1 | Aleah, Product & Engineering | "How your metrics actually work" |
| 2 | Gold/Platinum Pro (peer) | "What no one told you when you started" |
| 3 | Marketing rep | "Growing your business beyond the app" |
| 4 | Steve, CEO | "Why things work the way they do — and where it's going" |

**Format:** Katherine introduces each participant in the thread — they don't cold-start it. Participant answers replies as they come in, no schedule required. After 7–10 days (or when activity slows), Q&As are compiled into a Pro Academy post and archived so they remain searchable.

**Draft files:** `drafts/ama-steve-ceo.md`, `drafts/ama-product-engineering.md`, `drafts/ama-pro-peer.md`, `drafts/ama-marketing.md`

### Theme Rationale

Themes are grounded in community data:
- **Steve:** Pricing Issues (34 reactions), Lawn love competitor thread (25 reactions), FigJam LOW PAYOUTS + DISPUTES as top Pro pain points
- **Aleah:** Metrics is the #1 topic by every engagement measure — 3 of top 10 posts by replies (Performance metrics: 71, METRICS MAYHEM: 40, Metrics: 32)
- **Pro Peer:** Top peer content is practical and experiential (Client Before Pics: 26 replies, Tips and tricks: 30 reactions)
- **Marketing:** "Reviews for Google?" has 25 replies; flyers request cracks top 10 — Pros are already trying to grow off-platform

### Who Should Be Involved

- **Steve** — confirm before publishing; brief on current community tensions (metrics, pricing)
- **Aleah (PE)** — confirm she has capacity; brief on likely question types (metrics, Wishlist, app flow)
- **Gold/Platinum Pro** — first choice: Scott Culala (490 all-time replies, already acts as peer mentor organically); backup: Arely Elrod
- **Marketing rep** — identify and confirm; brief on GBP, Google reviews, local SEO

### Expected Outcome

The dominant unresolved topics get addressed by the people best positioned to answer them. Member-generated activity increases as Pros engage with voices they trust. Pro Academy builds a library of searchable expert answers that reduces repeat questions.

### How I'll Measure It

| Metric | Baseline | Target |
|--------|----------|--------|
| Admin share of total community activity | 32% | Under 25% by end of Q2 |
| AMA thread engagement (replies + reactions per thread) | 0 (new) | 20+ combined per thread |
| Pro Academy FAQ views | 0 (new) | 50+ views per compiled post within 30 days |

---

## Focus Area 5: Pool Pro Space

### The Problem

Pool Pros are a distinct service category with their own workflow, seasonality, and likely their own set of questions — but right now they land in the same community as lawn care Pros with no content built for them. There is a hidden space in Bettermode that can be activated for this. Before building anything, the discovery gap needs to close: we don't yet know what Pool Pros are actually asking, how their metrics work, or what frustrations are showing up in the existing LawnStarter-run Facebook page that Will and Shannon manage.

### What I'll Build in Bettermode

A **dedicated Pool Pro space** — activated from the existing hidden space, built out once discovery is complete.

Content will be determined by what comes out of the discovery phase, but likely includes:
- A Pool Pro equivalent of the First 60 Days series
- Field Guide posts for pool-specific problem scenarios
- Metrics and tier clarity content if pool Pro metrics differ from lawn care

### Discovery First — What I Need to Know Before Building

| Question | How to Answer |
|----------|--------------|
| What are Pool Pros actually asking and frustrated by? | Meeting with Trent M. (active community member, pool Pro) |
| What themes and complaints come up most on the Facebook page? | Sentiment pull from Will and Shannon |
| Do pool Pro metrics work differently from lawn care Pro metrics? | Confirm with Aleah or product team |
| What does the hidden space look like and what needs to change to activate it? | Review space settings in Bettermode admin |

### Who Should Be Involved

- **Trent M.** — Pool Pro, already active in the main community (10 posts, top contributor); first voice to consult
- **Will and Shannon** — manage the LawnStarter Pool Pro Facebook page; source of raw sentiment data that isn't captured anywhere in Bettermode yet
- **Aleah (PE)** — confirm whether pool Pro metrics are distinct from lawn care metrics before any tier/metrics content is written

### Expected Outcome

Pool Pros have a space that speaks to their work specifically. Sentiment and questions that currently live only on Facebook have a home in Bettermode — searchable, structured, and connected to support resources.

### How I'll Measure It

Baselines and targets to be set after discovery. Starting metrics will mirror the main community framework: space member count, post views, reply rate.

---

## What I'm NOT Doing (And Why)

| Idea | Why Not Now |
|------|-------------|
| Live/scheduled AMAs | Async format works better — no time zone problem, no scheduling lift, and the thread stays searchable. Live events were a one-time format; the rotation is ongoing. |
| General community building / engagement posts | Not a strategy. Every post needs to trace back to a problem. |
| Gamification / certifications | Future state. The platform problem has to be solved before the reward layer makes sense. |

---

## Data Gaps I Need to Fill

Before I can set hard baselines on the measurement targets above, I need:

1. **Zendesk ticket data**: Volume of new-Pro tickets (<60 days) by category (tier/rating, long grass, payment, unresponsive customer). One-time pull.
2. **New Pro completion rate at job 7**: What % of the current cohort reaches job 7? This is my baseline for Focus Area 1.
3. **Bettermode current engagement baseline**: How many active Pros are in Bettermode right now? What's the current post view rate?

I can pull items 1 and 2 from Brain/support data. Item 3 I can pull from Bettermode analytics directly.

---

## Summary

| Focus Area | Core Problem | Key Data Point | Primary Outcome |
|------------|-------------|----------------|-----------------|
| New Pro Success (0–60 days) | Half of new Pros don't reach job 10 | 20,796 → 10,217 by job 10; intervention window is jobs 1–7 | Reduce early attrition; reduce tier/rating support tickets from new Pros |
| High-Frequency Problem Scenarios | 40% of schedules hit a problem; Pros have no proactive guidance | 3.5% ticket-to-service ratio; 43% cancel rate on first-job issues | Deflect predictable support tickets; protect customer retention |
| Tier System Clarity | Rating/tier confusion is #3 support ticket; creates defensive Pro behavior | 35% → 63% Blue attainment lift possible in coachable middle | Reduce tier confusion tickets; increase Blue attainment in mid-rated Pros |
| Expert Access Rotation (AMA Series) | HQ drives 32% of all community activity; dominant topics need trusted expert voices | Metrics: 3 of top 10 posts by replies; 32% admin share of activity | Reduce admin activity share; build searchable library of expert answers on top Pro concerns |
| Pool Pro Space | Pool Pros have no dedicated community home; questions and sentiment live only on Facebook | Hidden Bettermode space exists but is unactivated; Facebook page is untapped signal | Give Pool Pros a dedicated space grounded in their actual problems |
