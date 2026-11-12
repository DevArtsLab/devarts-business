# Financial Plan

## Startup Costs

Actuals as of October 2026 - infrastructure is already running:

| Item                                           | Actual Cost                                                                                    |
| ---------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Domain (devartslab.com)                        | $15 via Amazon Route 53 (Jan 13, 2026); transfers to Cloudflare Nov 2, 2026, renewal $10.46/yr |
| Cloudflare Workers Paid                        | $5/mo ($60/yr)                                                                                 |
| Zone plan (devartslab.com)                     | $0 (Free; DNS fully managed in Cloudflare, AWS hosted zone removed)                            |
| AWS demo infra (documind)                      | Usage-based; teardown path documented                                                          |
| Software/Tools (Linear, GitHub, Notion, Figma) | $0 (free tiers)                                                                                |
| Marketing                                      | $0 (organic/referral to date)                                                                  |
| Legal/Business Registration                    | TBD                                                                                            |
| **Fixed total**                                | **~$75/yr + registration**                                                                     |

---

## Revenue Streams

1. **Project-Based Services** - One-time website builds and consulting
2. **Retainer/Subscription** - Ongoing maintenance and updates
3. **Product** - Self-hosted software (free core + paid setup/support; DEV-47)
4. **Product Sales** - Templates, tools, and digital assets
5. **Workshops/Training** - Teaching clients to manage their sites

---

## Pricing Strategy

_[Draft - proposed; validate against first client conversations]_

> Reference: [Pricing Guide for B2B SaaS Founders](../../vault/references/pricing-guide-b2b-saas.md) - customer discovery, value proposition, pricing models, packaging. (Encrypted vault content; readable in unlocked clones only.)

| Service              | Pricing Model | Range (proposed)                   |
| -------------------- | ------------- | ---------------------------------- |
| Portfolio Website    | Fixed         | $400-800                           |
| Business Website     | Fixed         | $1,500-3,500                       |
| E-commerce Setup     | Fixed         | $2,000-4,000                       |
| Custom App / AI work | Scoped        | $4,000+                            |
| Consulting           | Hourly        | $75-120/hr                         |
| Maintenance          | Monthly       | $30-150/mo                         |
| Product (DEV-47)     | Setup/support | $0 core; $150-300 setup (proposed) |

Approach: fixed-scope packages for predictability, monthly plans for
recurring revenue, scoped pricing for custom/AI work. Entry price kept
low to maximize early feedback (guide: price low, learn, graduate).
Full rationale and market anchors: [Pricing Strategy](Pricing-Strategy.md).

### Cost advantage (product track)

Self-hosted + local LLM means $0 recurring COGS per user; hosted
incumbents carry LLM API cost inside $26-40/mo subscriptions. Edge
stack (Workers + D1 + R2 free tiers) covers a future hosted beta.
Compliance costs stay zero while the product is self-hosted; a hosted
tier would add ~$675-5,400/yr CASA assessment plus ~6-week Google
restricted-scope verification (DEV-47, verified 2026-10-26).

---

## Revenue Projections

_[Draft - proposed; Year 2 window (Nov 2026 - Oct 2027). No paying pilots yet - projections assume first paid work lands in Q1.]_

| Period              | Projected Revenue | Notes                                   |
| ------------------- | ----------------- | --------------------------------------- |
| Nov 2026 - Jan 2027 | $0-2,000          | Outreach, 1-2 starter/professional jobs |
| Feb - Apr 2027      | $2,000-6,000      | 1-2 business sites + first retainers    |
| May - Oct 2027      | $6,000-15,000     | 3-5 projects, recurring plans compound  |
| **Year 2 Total**    | **$8,000-23,000** | Conservative; upside via RTS (DEV-18)   |

---

## Expenses

| Category                                       | Monthly | Annual   |
| ---------------------------------------------- | ------- | -------- |
| Hosting/Infrastructure (Workers Paid + domain) | ~$6     | ~$70     |
| Software Subscriptions                         | $0      | $0       |
| Marketing                                      | $0      | $0       |
| Professional Services                          | TBD     | TBD      |
| **Total**                                      | **~$6** | **~$70** |

---

## Break-Even Analysis

_[Draft - proposed]_

Fixed costs ~$75/yr + registration (TBD). Break-even is effectively one
Starter project (~$400). Real threshold is founder time, not cash: the
constraint is converting delivery hours into repeatable packages before
taking on scoped work.

---

## Funding Requirements

_[Draft - proposed]_

No external funding required at current burn (~$75/yr infra). Needs:

| Item                       | Est. Cost      | Timing                                 |
| -------------------------- | -------------- | -------------------------------------- |
| Business registration/LLC  | TBD            | Before paid work                       |
| Domain + Workers Paid      | ~$75/yr        | Running                                |
| Contingency (tools, ads)   | ~$500          | As needed                              |
| n8n license confirmation   | $0             | Before paid product launch             |
| CASA + Google verification | ~$675-5,400/yr | Only if hosted tier returns (deferred) |

---

<- [[Operations Plan]] | [[Home]] | [[Milestones]] ->
