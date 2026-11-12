# Pricing Strategy

_[Draft - proposed, Oct 2026. Anchors verified via Linear-tracked research;
tiers pending validation against first client conversations.]_

> Reference: [Pricing Guide for B2B SaaS Founders](../../vault/references/pricing-guide-b2b-saas.md)
> (Stripe 2023, encrypted vault, unlocked clones only). This page distills
> the guide's framework and binds it to market data tracked on Linear.

---

## Guide principles applied

| Principle (guide)                        | How it lands here                                                          |
| ---------------------------------------- | -------------------------------------------------------------------------- |
| Pick the order of magnitude first        | $100s for portfolios, $1Ks for business sites, $4K+ scoped for custom/AI   |
| Extract ~10-15% of value delivered       | AI automation priced against hours saved, not feature lists                |
| Low entry price, graduate upward         | Starter at $400-800 lowers the barrier; packages carry a growth path       |
| Complexity kills                         | Three tiers + four add-ons; no feature matrices                            |
| Freemium cautiously                      | Product core ships free for reach; services never free                     |
| Cost and price scale together            | Edge + self-hosted stack keeps COGS near $0; recurring plans fund support  |
| Pricing shapes go-to-market              | Low-price packages run self-serve/referral; $4K+ scoped work runs proposal |

---

## Market anchors

Signals tracked on Linear (DEV-125 market scan 2026-10-28, DEV-47
competitive survey re-verified 2026-10-27):

| Anchor                                                    | Figure                                  | Pricing implication                                          |
| --------------------------------------------------------- | --------------------------------------- | ------------------------------------------------------------ |
| Hosted career-tool incumbents (Huntr, Teal, Simplify+)    | $26-40/mo effective                     | Self-hosted product undercuts on total cost of ownership     |
| Agentic-systems roles                                     | $225K median comp                       | $75-120/hr consulting sits below replacement cost of a hire  |
| AI skills in US tech postings                             | 36%                                     | AI add-ons are a growth attach, not a niche upsell           |
| Exec AI-ROI pain (Bain/BCG 2025)                          | ~2/3 deployed genAI, unclear ROI        | Sell outcome scorecards (time saved, error rate), not "AI"   |
| Agentic AI posting growth (Dice 2025)                     | +2043% YoY; RAG +475%, edge +608%       | Enterprise tier anchored on agentic pipeline scope           |
| CASA assessment (only if a hosted SaaS tier ever returns) | ~$675-5,400/app/yr                      | Hosted tier must clear ~$8K+/yr revenue to justify compliance |

---

## Two revenue tracks

### Services track (now)

Fixed-scope packages, monthly plans, scoped custom work.
See [Products and Services](Products-and-Services.md#service-packages) for
the tier table. Constraint: founder hours; pricing converts delivery time
into repeatable packages.

### Product track (DEV-47, in development)

Self-hosted single-tenant software (Docker Compose distribution, local
LLM at $0 recurring COGS). Monetization options ranked by gate size:

| Option                   | Price shape        | Gate                                                                |
| ------------------------ | ------------------ | ------------------------------------------------------------------- |
| Free core (OSS)          | $0                 | None - reach and credibility engine                                 |
| Paid setup + support     | $150-300 one-time  | Low - services motion, already permitted                            |
| Paid product license     | TBD                | Medium - n8n SUL needs written confirmation before paid launch      |
| Hosted tier (deferred)   | ~$10-20/mo         | High - parked per DEV-47 Q18; CASA + verification costs apply       |

Free core is deliberate, not freemium drift: the guide warns free users
can devalue a brand, so the free artifact is a complete product (data
ownership, local LLM) and the paid layer is labor and convenience, which
hosted incumbents cannot bundle at $26-40/mo.

---

## Value pricing for AI work

AI automation add-ons price against a scorecard, not effort:

- Baseline the client's manual cost (hours/task, error rate, cycle time).
- Price at ~10-15% of quantified annual value where measurable.
- Report delivered value in DORA/SPACE vocabulary (lead time, throughput,
  failure rate, time saved) - the scorecard execs say is missing.

## Open pricing decisions (product gates)

- Product license vs setup/support-only model (blocked on n8n license
  confirmation, DEV-47 Q21).
- Consulting rate band vs value-priced fixed quotes once 3-5 projects
  land.
- Whether Year 2 adds a paid template/asset line (low-touch revenue).

---

<- [[Financial Plan]] | [[Home]] | [[Products and Services]] ->
