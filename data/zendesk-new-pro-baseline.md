# Zendesk Baseline: New-Pro Tickets

**Source:** Matt's Retention Discovery — Support Data & Bettermode Findings
**Branch:** `matt/retention-support-data-findings`
**File:** `docs/swim-lanes/retention/research/2026-03-26-support-data-findings.md`
**Data pulled by Matt:** March 26, 2026 | Covers March 2025–March 2026 (12 months)
**Extracted by:** Kat Kennedy, April 21, 2026

> **Caveat on tenure filter:** Matt's data segments by Pro tier (New tier = Intro/Red/Blue), not by exact days-on-platform. New tier includes Pros in their first 3 months OR with fewer than 20 jobs in the last 12 months. This is the closest available proxy for "first 60 days" without a direct Zendesk pull. Numbers are directionally reliable; treat as baseline, not exact.

---

## New-Tier Ticket Volume by Subcategory (12 months, n=~235K matched tickets)

| Subcategory | New-Tier Tickets | Maps To |
|---|---|---|
| payouts_fees | **12,041** | Payment / payout questions |
| account_help | **10,863** | Tier confusion + account status |
| service_help (general) | **9,408** | General service help, scope confusion, app blocks |
| scheduling_problem | **6,099** | Scheduling issues |
| help_with_dispute | **5,527** | Dispute resolution |
| pricing_problem | **5,079** | Pricing complaints, underpriced jobs |
| long_grass_problem | **3,986** | Long grass reporting and disputes |
| schedule_change_request | **3,331** | Rescheduling |
| completion_problem | **3,215** | Job marked incomplete, photo upload failures |
| banking | **2,872** | Stripe setup, first payout, 1099 |
| service_skip | **1,557** | Skipped job handling |
| technical_help | **1,354** | App login, crashes, photo upload broken |
| scheduling_complaints | **1,625** | Scheduling system frustrations |
| property_obstruction | **1,229** | Locked gates, animals, debris |
| account_information | **1,240** | Basic account questions |
| reactivation | **843** | Account reactivation |
| property_damage | **317** | Damage reporting |
| deactivation | **307** | Account deactivation |
| quote_or_service_detail | **3,956** | Service scope and quote details |

---

## Mapped to Our 5 Strategy Categories

| Strategy Category | Closest Subcategory(ies) | New-Tier Volume | Notes |
|---|---|---|---|
| Payment / payout | payouts_fees + banking | **~14,913** | #1 by a wide margin. First payout delay is the top theme — new Pros working weeks with no payment. |
| Tier / rating confusion | account_help (partial) | **~10,863** | account_help includes non-solicitation notices, deactivations, and new Pro orientation ("why no jobs", "how does Stripe work"). Pure tier/metrics confusion is also buried in service_help and has almost NO Zendesk category — Pros can't resolve it via support so it spills into Bettermode instead (see below). |
| General service + scope | service_help | **~9,408** | App won't let me complete job, scope confusion ("does mowing include edging?"), unexpected property conditions. |
| Long grass | long_grass_problem | **~3,986** | No in-app claim path is the top complaint. Intro Pros disproportionately represented — they haven't learned to screen or decline overgrown properties. |
| Unresponsive customer / cancellation | scheduling_problem + service_help (partial) | **~6,099+** | No clean subcategory. Embedded in scheduling_problem and service_help. Customer cancellation requests specifically surface in qualitative themes but aren't a standalone subcategory. |

---

## Bettermode Signal (Supplements Zendesk)

Matt's doc also analyzed all 337 original posts in Bettermode's Ask the Community space. This fills the gap where Zendesk undercounts:

| Bettermode Category | Posts | Replies | Key Insight |
|---|---|---|---|
| Metrics & Performance System | 30 | 92 | **#1 retention risk topic.** Pros can't resolve metric confusion through support — it has no Zendesk category. Community absorbs it entirely. |
| Pricing, Commission & Pay | 35 | 107 | Highest replies-per-post ratio (~3.1). 38.89% markup on Manual Quotes is eroding customer relationships. |
| Scheduling & Job Management | 41 | 100 | System-generated reschedule dings, route optimization removed, no pre-drive cancellation alerts. |
| App & Technical Issues | 35 | 97 | March 2026 update introduced regressions at start of peak season. |
| New Pro Onboarding | 11 | 30 | "I haven't gotten a customer yet", "So lost" — onboarding sets no expectations about metrics, payment timing, or commission structure. |

---

## Priority Order for Content (Data-Backed)

Based on this data, here's the revised priority for Field Guide and First 60 Days content:

| Priority | Topic | Why |
|---|---|---|
| **#1** | Payment / how and when you get paid | 14,913 new-tier tickets. First payout delay is the #1 trust-breaking moment. Easy to explain, high deflection potential. |
| **#2** | Tier system / metrics explainer | Biggest Bettermode topic with essentially zero Zendesk resolution. Only Bettermode can absorb this. |
| **#3** | Long grass | 3,986 tickets, clear recurring confusion, well-documented cause. Highly deflectable with a good content piece. |
| **#4** | What to do when the customer cancels | No app option exists, buries in scheduling + service_help. High frequency, easy to explain the workaround. |
| **#5** | Completing a job correctly (photos, app flow) | completion_problem + service_help = ~12,600 tickets combined. Photo upload failure is a cross-category blocker. |

---

## Notable Quotes from Pros (Matt's Qualitative Pull)

On payment:
> *"We are not doing any jobs until we get paid for the ones we have done. We have worked a whole month without pay."* [unknown tier]
> *"Nobody wants to wait a week to get paid from their hard work when they own their own business."* [intro]

On tier/metrics:
> *"I have never had an incomplete job... yet because of customers skipping service at their discretion, my completion rate tanks."*
> *"Can someone please explain the percent of jobs completed performance metric?"* (12 replies — most engaged metrics post)

On long grass:
> *"That grass was between 9 to 15 inches... It took me almost 5 hours to cut the grass. There is no option on this app for long grass."* [intro]

On new Pro experience:
> *"So lost"* / *"I haven't gotten a customer yet"* — peer community is functioning as the only structured onboarding resource.

---

## How This Is Used

- Sets baselines for Focus Areas 1, 2, and 3 measurement targets
- Priority order above replaces the assumed order in the strategy doc
- Feeds monthly tracking in task 20
- Source: no Zendesk access needed — Matt's discovery covers this
