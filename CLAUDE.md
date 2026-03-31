# CLAUDE.md

## Repository Overview

This is `skgalara/skgalara`, a **GitHub profile repository**. On GitHub, a repository named the same as the username is special: its `README.md` is rendered directly on the user's public profile page at `github.com/skgalara`.

## Repository Structure

```
skgalara/
└── README.md   # GitHub profile page content (rendered on profile)
```

There is no source code, build system, test suite, or CI/CD pipeline. This is a purely content/documentation repository.

## Purpose

The sole purpose of this repository is to maintain the content displayed on the GitHub profile. The `README.md` supports full GitHub-flavored Markdown (GFM), including:

- Badges and shields
- Embedded images and GIFs
- Tables
- HTML (limited subset)
- Emoji shortcodes

## Development Workflow

### Making Changes

1. Edit `README.md` directly.
2. Commit and push to `main` — changes appear on the profile immediately.

```bash
git add README.md
git commit -m "Update profile: <short description>"
git push origin main
```

### Branching

For significant rewrites or experimental layouts, use a feature branch and merge to `main` when satisfied.

## Conventions

- Keep `README.md` concise and professional — it is the first thing visitors see.
- Do not add source code, scripts, or configuration files unless they serve the profile display directly (e.g., a GitHub Actions workflow that auto-updates stats).
- Prefer relative links for any assets stored in this repository.
- If adding images, keep file sizes small for fast profile load times.

## Current README State

The README currently contains the default GitHub template with placeholder text (interests, learning goals, collaboration interests, contact info, pronouns, fun fact). It has not yet been customized.

## AI Assistant Notes

- There is nothing to build, test, lint, or compile.
- The only meaningful task in this repo is editing `README.md`.
- Any automation (e.g., profile stats badges, activity graphs) would require adding a `.github/workflows/` directory with the appropriate GitHub Actions workflow.
- When suggesting changes, prefer content that reflects the user's actual background and interests over generic placeholder text.
