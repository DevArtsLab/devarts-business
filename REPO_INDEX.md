# REPO_INDEX.md - devarts-business

> Single source of truth for what lives in this repository.
> Regenerate when files or folders are added, removed, or substantially rewritten.
>
> **Last updated:** 2026-10-29

## Top-level

| Path             | What it is                                                           |
| ---------------- | -------------------------------------------------------------------- |
| `README.md`      | Entry point: stage, live site, links into `docs/wiki/`               |
| `REPO_INDEX.md`  | This index                                                           |
| `AGENTS.md`      | Agent-facing conventions; foundation adoption (rev 3a)               |
| `.gitignore`     | macOS junk, Obsidian churn, git-crypt key material                   |
| `.gitattributes` | git-crypt filter: everything under `vault/` encrypted at rest in git |
| `docs/`          | Business plan documentation set                                      |
| `vault/`         | Encrypted Obsidian vault: external communications log                |

## docs/wiki/

| File                               | What it is                                                 | Status                 |
| ---------------------------------- | ---------------------------------------------------------- | ---------------------- |
| `Home.md`                          | Wiki landing page, mission, document status table          | Current                |
| `Business-Overview.md`             | Executive summary, mission, vision, values                 | Complete               |
| `Products-and-Services.md`         | Offerings, service detail, future offerings (DEV-16/17/18) | In progress (pricing)  |
| `Market-Analysis.md`               | Target segments, personas, competitors                     | Pending (placeholders) |
| `3-Minute-Pitch.md`                | Problem, segments, UVP, partners, metrics                  | In progress (script)   |
| `Operations-Plan.md`               | Tech stack, tools, client workflow                         | Complete               |
| `Financial-Plan.md`                | Actual infra costs, revenue streams, projections           | In progress (pricing)  |
| `Milestones.md`                    | Year 1 roadmap, phases, risk analysis                      | Complete               |
| `Repository-Naming-Conventions.md` | Naming standards for DevArtsLab org repos                  | Complete               |

## docs/ (outside wiki)

| Path              | What it is                                                                               |
| ----------------- | ---------------------------------------------------------------------------------------- |
| `activity-log.md` | DevArts Lab activity log: programs, events, external inputs (records, not plan sections) |
| `records/`        | Archived records linked from the activity log                                            |

## docs/records/

| File                             | What it is                                                             |
| -------------------------------- | ---------------------------------------------------------------------- |
| `first-stage-lab-cohort-3.md` | ULEM First Stage Lab Cohort 3 (Nov-Dec 2025) participation record |

## docs/legal/

| File                  | What it is                             |
| --------------------- | -------------------------------------- |
| `privacy-policy.md`   | Privacy policy, effective 2026-02-01   |
| `terms-of-service.md` | Terms of service, effective 2026-02-01 |

## vault/

| Path                                   | What it is                                                 |
| -------------------------------------- | ---------------------------------------------------------- |
| `vault/README.md`                      | Vault layout, git-crypt unlock instructions                |
| `vault/communications/Index.md`        | Dataview index over communication notes                    |
| `vault/communications/YYYY/quarter-N/` | Archived master records (do not alter after filing)        |
| `vault/templates/`                     | Note templates (Communication Log)                         |
| `vault/.obsidian/`                     | Obsidian config + Dataview plugin (workspace.json ignored) |

## External references

| Where                      | What                                                                    |
| -------------------------- | ----------------------------------------------------------------------- |
| `../devartslab-foundation` | Governing charter; adopted revision 3a (2026-10-26)                     |
| Linear project `P-DEV-2`   | DevArts Lab Business Buildout: DEV-16/17/18 backlog, DEV-19 in progress |
| `../LAB_INDEX.md`          | Workspace inventory (this repo listed under research/notes)             |
