# Tracking: New Pro Tier Progression — 60-Day Blue Attainment
**Owner:** Kat Kennedy
**Cadence:** Monthly cohort pull — run at day 30 and day 60 for each cohort
**Purpose:** Track what share of new Pros reach Blue tier within 60 days of completing their first job. Measures whether First 60 Days content is moving the needle on the outcome that matters most.

---

## Background

New Pros (< 3 months on platform OR < 20 mowing jobs) are on a separate tier scale: **Blue → Intro → Red**.

Blue requires all three:
| Metric | Blue threshold |
|---|---|
| Review surplus | +3 or higher (sum of all ratings minus 4 × number of ratings) |
| Completion rate | 55% or higher |
| Cancellation rate | 8% or lower |

Tier updates weekly while on the new Pro scale. A Pro who hits all three thresholds in a given week is in Blue the following week.

**Why 60 days:** Most Pros either reach Blue or stall out within their first 8 weeks. By day 60, trajectory is set. This is also the window the First 60 Days content series is designed to cover.

**Known baseline (pre-strategy content):**
- 56.2% of new Pros reach job 7 (11,685 / 20,796) — from Matt's retention discovery
- Pros averaging 4.8+ at 3 ratings: 65% reach Blue
- Pros averaging 4.5+: 53–66% reach Blue
- Pros averaging 4.0–4.4: 35% reach Blue
- Pros who reach Blue are significantly more likely to still be active at job 10

---

## How to Pull

This is **platform data, not Bettermode data.** Requires a Redshift query or a data team pull.

### What to request from the data team

> "For Pros who completed their first job in [week/month], how many reached Blue tier within 30 days? Within 60 days? Pull as a weekly cohort table — one row per cohort week, columns for cohort size, Blue by day 30, Blue by day 60."

Key fields needed:
- `pro_id`
- Date of first completed job (cohort anchor date)
- Tier at day 30 from first job
- Tier at day 60 from first job (or current tier + days since first job if < 60 days)

### Cohort definition

- **In:** Pro completed their first job (not just joined — completed)
- **Out:** Pros who never completed a job, pro-initiated cancellations before first completion
- **Window:** 60 days from the date of their first completed job

---

## Cohort Tracker

One row per weekly cohort. Pull at day 30 and day 60 for each cohort.

| Cohort (First Job Week) | Cohort Size | Blue by Day 30 | % Blue D30 | Blue by Day 60 | % Blue D60 | Notes |
|---|---|---|---|---|---|---|
| Week of Apr 28, 2026 | | | | | | First week First 60 Days content was live |
| Week of May 5, 2026 | | | | | | |
| Week of May 12, 2026 | | | | | | |
| Week of May 19, 2026 | | | | | | |
| Week of May 26, 2026 | | | | | | |
| Week of Jun 2, 2026 | | | | | | |
| Week of Jun 9, 2026 | | | | | | |
| Week of Jun 16, 2026 | | | | | | |
| Week of Jun 23, 2026 | | | | | | |

---

## Pre-Content Baseline Cohorts

Pull these retroactively to establish what Blue attainment looked like before any First 60 Days content was live. Use as the comparison point.

| Cohort (First Job Week) | Cohort Size | Blue by Day 30 | % Blue D30 | Blue by Day 60 | % Blue D60 | Notes |
|---|---|---|---|---|---|---|
| Week of Feb 23, 2026 | | | | | | |
| Week of Mar 2, 2026 | | | | | | |
| Week of Mar 9, 2026 | | | | | | |
| Week of Mar 16, 2026 | | | | | | |
| Week of Mar 23, 2026 | | | | | | |
| Week of Mar 30, 2026 | | | | | | |
| Week of Apr 6, 2026 | | | | | | |
| Week of Apr 13, 2026 | | | | | | |
| Week of Apr 20, 2026 | | | | | | Pre-content; 60 days closes ~Jun 19 |

---

## Monthly Summary

Update once enough cohorts have hit their day-60 mark (first full read available ~late June 2026).

| Month (cohort start) | Total new Pros | Blue by D60 | % Blue D60 | vs. baseline | Notes |
|---|---|---|---|---|---|
| Feb–Mar 2026 (pre-content) | | | | — | Baseline |
| Apr–May 2026 | | | | | Partial overlap with content launch |
| May–Jun 2026 | | | | | First full cohort exposed to all 4 posts |

---

## What Success Looks Like

No explicit target has been set for Blue attainment rate yet — this tracker establishes the baseline. Once pre-content cohorts are pulled, set a target for the first post-content cohorts.

**Suggested target (set after baseline pull):** 5–10 percentage point lift in % Blue by Day 60 for cohorts who completed their first job after 4/30/2026.

**Supporting signal to watch alongside this:**
- Bettermode post views on tasks 9 + 10 (tier score + getting to Blue) — tracked in `data/tracking-bettermode-weekly.md`
- If views are high but Blue attainment doesn't improve, the content is being read but not acted on → investigate which step breaks down

---

## Notes

- **Cohort anchor = first completed job, not join date.** Join date is easier to pull but less meaningful — Pros who join and never complete a job aren't in the funnel.
- **Day 60 is a hard window.** A Pro who reaches Blue on day 61 doesn't count. This is intentional — the content targets the first 60 days, so the metric should match.
- **Seasonal effects:** Spring is peak lawn care season. Expect higher cohort sizes and potentially higher Blue attainment in Apr–Jun than in fall cohorts. Note seasonality when comparing across quarters.
- **Related files:** `data/bettermode-growth-tracker.md` (community-level), `data/tracking-bettermode-weekly.md` (per-post views), `data/bettermode-baseline.md` (Apr 21 community baseline)
