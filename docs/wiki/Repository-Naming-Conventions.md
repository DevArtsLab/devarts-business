# Repository Naming Conventions

Naming standards for repositories in the DevArtsLab GitHub org.

## Format

- All lowercase kebab-case: `my-project-name`
- No snake_case, PascalCase, spaces, or underscores
- Short but descriptive; avoid abbreviations that are not obvious

## Prefixes

| Prefix        | Use                                   | Examples                                           |
| ------------- | ------------------------------------- | -------------------------------------------------- |
| `devartslab-` | Public web properties                 | `devartslab-site`, `devartslab-notion`             |
| `devarts-`    | Internal tooling and business docs    | `devarts-mail`, `devarts-business`                 |
| `tool-`       | Reusable utilities and helper scripts | `tool-airtable-export`, `tool-universal-ai-config` |

Project, client, and experiment repos use plain descriptive names with no
prefix: `voice-quote`, `documind`, `health-pulse`.

## Type suffixes

Add a suffix when the name alone is ambiguous:

- `-site`: static site or landing page
- `-app`: interactive web app
- `-api`: API-only service
- `-worker`: Cloudflare Worker service
- `-cli`: command-line tool
- `-pipeline`: data or ML pipeline
- `-viewer`: read-only browsing UI
- `-export`: data export or backup tool

## About section

Every repo should have:

- Description: one line, `<what it does> - <stack or notable detail>`
- Homepage: public URL if one exists
- Topics: 3-6 lowercase tags covering stack and domain

## Local clones

Local directory names must match the repo name exactly. If a repo is renamed
on GitHub, rename the local directory and update the remote URL:

```bash
git remote set-url origin <new-url>
```

## Renaming a repo

```bash
gh repo rename <new-name> -R DevArtsLab/<old-name>
```

GitHub keeps redirects from the old name, so existing links keep working.
