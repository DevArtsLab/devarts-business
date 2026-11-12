# Products and Services

## Core Offerings

| Service                               | Description                                                                                    |
| ------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Organization Intelligence System**  | Salesforce + n8n systems pipeline automation                                                   |
| **Digital Transformation Consulting** | Helping traditional businesses establish their online presence                                 |
| **AI Automation & Agents**            | Agentic AI systems: RAG document Q&A, research agents, async pipelines for client workflows    |
| **Custom Websites & Portfolios**      | Modern, responsive websites                                                                    |
| **AI-Assisted Content Creation**      | Project research, branding                                                                     |
| **E-commerce Setups**                 | Online stores for small businesses                                                             |
| **Managed Deployment**                | Edge/serverless hosting with Workers, DNS, and email setup with low-maintenance infrastructure |

---

## Service Packages

_[Draft - proposed pricing, pending validation against first client conversations]_

> Reference: [Pricing Guide for B2B SaaS Founders](../../vault/references/pricing-guide-b2b-saas.md) - packaging and tiering patterns. (Encrypted vault content; readable in unlocked clones only.)
> Guide principles applied: low entry price, tiers differentiated by
> scope/quantum rather than feature gating, room to graduate upward.

| Package          | Features                                                                                             | Price Range (proposed)     |
| ---------------- | ---------------------------------------------------------------------------------------------------- | -------------------------- |
| **Starter**      | Portfolio or landing page (1-3 pages), responsive design, contact form, managed edge hosting setup   | $400-800 one-time          |
| **Professional** | Multi-page business site (5-10 pages), e-commerce or booking setup, custom domain + email, basic SEO | $1,500-3,500 one-time      |
| **Enterprise**   | Custom web app or AI automation pipeline, integrations (CRM, payments), documentation, training      | $4,000+ scoped per project |

Tier rationale and market anchors: [Pricing Strategy](Pricing-Strategy.md).

### Add-Ons (proposed)

| Add-on                    | Model   | Range        |
| ------------------------- | ------- | ------------ |
| Managed hosting + support | Monthly | $30-80/mo    |
| Content updates           | Monthly | $50-150/mo   |
| AI automation add-on      | Project | $1,000-3,000 |
| Consulting / audit        | Hourly  | $75-120/hr   |

Rate anchor: agentic-systems roles carry $225K median comp (DEV-125
scan); $75-120/hr prices below the fully-loaded cost of a specialist
hire while staying above commodity freelance rates.

---

## Product Line (in development - DEV-47)

**Career tracker (self-hosted, single-tenant):** job-hunt records and
email threads built from the user's own correspondence, agentic pipeline
on local LLM (Ollama), Neuro-SAN agent layer, n8n ingest workflows.
Distribution: Docker Compose + install script + web install/upgrade
wizard; data stays on user hardware.

| Property          | Decision (DEV-47, 2026-10-28)                                  |
| ----------------- | -------------------------------------------------------------- |
| Distribution      | GHCR images, semver-pinned compose, `TRACKER_VERSION` in .env  |
| Release channel   | GitHub releases (immutable), CTD catalogs as release snapshots |
| Ingest            | Per-user Gmail OAuth; forwarding-based fallback                |
| AI cost           | $0 recurring - local models, BYOK option                       |
| Monetization (v1) | Free core; paid setup/support; paid license gated on n8n SUL   |
| Hosted SaaS tier  | Deferred until demand evidence (CASA ~$675-5,400/yr applies)   |

vs hosted incumbents ($26-40/mo, cloud-only): the moat is data
ownership + $0 recurring AI cost + a thread model no competitor ships.

---

## Detailed Service Descriptions

### Custom Websites & Portfolios

- Packages, libraries, and tools for developers and designers
- End-to-end organization workflow development
- Business websites for local shops and service providers
- Solutions for product launches and campaigns

### AI-Assisted Content Creation

- Project research and documentation
- Brand messaging and taglines

### E-commerce Setups

- Product catalog setup
- Payment integration
- Order management systems
- Inventory tracking

### Digital Transformation Consulting

- Digital presence audit
- Website strategy planning
- Technology recommendations
- Implementation roadmap

---

## Future Offerings

- [ ] Career tracker v1 release (self-hosted, DEV-47 Phases A-D)
- [ ] Async research agent service (Linear: DEV-16)
- [ ] Productized Revenue Transformation System (RTS) onboarding for partner organizations and consultants (Linear: DEV-18)
- [ ] Studio storefront with embedded live demos (Linear: DEV-17)
- [ ] Paid product license or hosted tier (post-launch, on demand evidence)
- [ ] Maintenance and support packages
- [ ] Workshops and training programs

---

<- [[Business Overview]] | [[Home]] | [[Market Analysis]] ->
