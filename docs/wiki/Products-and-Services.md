# Products and Services

## Core Offerings

| Service                               | Description                                                                              |
| ------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Organization Intelligence System**  | Salesforce + n8n systems pipeline automation                                             |
| **Digital Transformation Consulting** | Presence audit, website strategy, technology recommendations, implementation roadmap     |
| **AI Automation & Agents**            | Agentic systems: RAG document Q&A, research agents, async pipelines for client workflows |
| **Custom Websites & Portfolios**      | Business sites for local shops, professional portfolios, product and campaign pages      |
| **AI-Assisted Content Creation**      | Project research and documentation, brand messaging                                      |
| **E-commerce Setups**                 | Product catalog, payment integration, order management, inventory tracking               |
| **Managed Deployment**                | Edge/serverless hosting, DNS, and email on low-maintenance infrastructure                |

---

## Service Packages

_[Draft - proposed pricing, pending validation against first client conversations]_

This page is the single home for price figures; other pages link here.
Tiering rationale: [Pricing Strategy](Pricing-Strategy.md).

| Package          | Features                                                                                             | Price (proposed)           |
| ---------------- | ---------------------------------------------------------------------------------------------------- | -------------------------- |
| **Starter**      | Portfolio or landing page (1-3 pages), responsive design, contact form, managed edge hosting setup   | $400-800 one-time          |
| **Professional** | Multi-page business site (5-10 pages), e-commerce or booking setup, custom domain + email, basic SEO | $1,500-3,500 one-time      |
| **Enterprise**   | Custom web app or AI automation pipeline, integrations (CRM, payments), documentation, training      | $4,000+ scoped per project |

### Add-Ons (proposed)

| Add-on                    | Model   | Range        |
| ------------------------- | ------- | ------------ |
| Managed hosting + support | Monthly | $30-80/mo    |
| Content updates           | Monthly | $50-150/mo   |
| AI automation add-on      | Project | $1,000-3,000 |
| Consulting / audit        | Hourly  | $75-120/hr   |

---

## Product Line (in development - DEV-47)

**Career tracker (self-hosted, single-tenant):** job-hunt records and
email threads built from the user's own correspondence, agentic pipeline
on local LLM (Ollama), Neuro-SAN agent layer, n8n ingest workflows.
Distribution: Docker Compose + install script + web install/upgrade
wizard; data stays on user hardware.

| Property          | Decision (DEV-47, 2026-10-28)                                                                           |
| ----------------- | ------------------------------------------------------------------------------------------------------- |
| Distribution      | GHCR images, semver-pinned compose, `TRACKER_VERSION` in .env                                           |
| Release channel   | GitHub releases (immutable), CTD catalogs as release snapshots                                          |
| Ingest            | Per-user Gmail OAuth; forwarding-based fallback                                                         |
| AI cost           | $0 recurring - local models, BYOK option                                                                |
| Monetization (v1) | Free core; paid setup/support ($150-300 proposed); paid license gated on n8n SUL confirmation           |
| Hosted SaaS tier  | Deferred until demand evidence; adds CASA ~$675-5,400/yr + ~6-week Google restricted-scope verification |

Differentiation vs hosted incumbents: [Market Analysis](Market-Analysis.md#competitor-analysis).
Moat: data ownership + $0 recurring AI cost + a thread model no competitor ships.

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
