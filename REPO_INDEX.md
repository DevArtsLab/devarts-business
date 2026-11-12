# REPO_INDEX.md - devarts-business

> Single source of truth for what lives in this repository.
> Regenerate when files or folders are added, removed, or substantially rewritten.
>
> **Last updated:** 2026-11-11 at 11:18 PM EST

## Rules

- One home per fact. Identity in `docs/wiki/Business-Overview.md`,
  prices in `docs/wiki/Products-and-Services.md`, market figures in
  `docs/wiki/Market-Analysis.md`. Every other page links; nothing restates.
- Document readiness is tracked once in `../LAB_INDEX.md`
  (foundation `reference/repo-layout` S16.2), not in this index.

## Top-level

| Path             | What it is                                                           |
| ---------------- | -------------------------------------------------------------------- |
| `README.md`      | Entry point: what this repo is, links into `docs/`                   |
| `REPO_INDEX.md`  | This index                                                           |
| `AGENTS.md`      | Agent-facing conventions; foundation adoption (rev 3a)               |
| `.gitignore`     | macOS junk, Obsidian churn, git-crypt key material                   |
| `.gitattributes` | git-crypt filter: everything under `vault/` encrypted at rest in git |
| `docs/`          | Business plan documentation set                                      |
| `vault/`         | Encrypted Obsidian vault: external communications log                |

## docs/wiki/

| File                               | What it is                                                           |
| ---------------------------------- | -------------------------------------------------------------------- |
| `Home.md`                          | Wiki landing page and navigation                                     |
| `Business-Overview.md`             | Identity facts, mission, vision, values (home for business identity) |
| `Products-and-Services.md`         | Offerings, service packages, product line (home for all prices)      |
| `Market-Analysis.md`               | Demand signals, segments, personas, competitors (home for figures)   |
| `Pricing-Strategy.md`              | Pricing rationale, guide distillation, open gates; cites the homes   |
| `Financial-Plan.md`                | Cost actuals, revenue streams, projections, funding                  |
| `Operations-Plan.md`               | Tech stack, tools, delivery workflow                                 |
| `Milestones.md`                    | Year 1 retrospective, Year 2 roadmap, risks                          |
| `3-Minute-Pitch.md`                | Talk track; cites fact homes instead of restating numbers            |
| `First-Stage-Lab-Application.md`   | ULEM First Stage Lab Cohort 3 record (Nov-Dec 2025)                  |
| `Repository-Naming-Conventions.md` | Naming standards for DevArtsLab org repos                            |

## docs/legal/

| File                  | What it is                             |
| --------------------- | -------------------------------------- |
| `privacy-policy.md`   | Privacy policy, effective 2026-02-01   |
| `terms-of-service.md` | Terms of service, effective 2026-02-01 |

## vault/

| Path                                   | What it is                                                             |
| -------------------------------------- | ---------------------------------------------------------------------- |
| `vault/README.md`                      | Vault layout, git-crypt unlock instructions                            |
| `vault/communications/Index.md`        | Dataview index over communication notes                                |
| `vault/communications/YYYY/quarter-N/` | Archived master records (do not alter after filing)                    |
| `vault/references/`                    | Third-party source docs kept encrypted (copyright); pricing guide etc. |
| `vault/templates/`                     | Note templates (Communication Log)                                     |
| `vault/.obsidian/`                     | Obsidian config + Dataview plugin (workspace.json ignored)             |

## External references

| Where                    | What                                                                    |
| ------------------------ | ----------------------------------------------------------------------- |
| `../foundation`          | Governing charter; adopted revision 3a (2026-10-26)                     |
| Linear project `P-DEV-2` | DevArts Lab Business Buildout: DEV-16/17/18 backlog, DEV-19 in progress |
| `../LAB_INDEX.md`        | Workspace inventory and document readiness                              |
