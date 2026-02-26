# CONTRIBUTING.md Design

**Date:** 2026-02-27
**Status:** Approved

## Purpose

Add a `CONTRIBUTING.md` to the Kausora Technologies `.github` repo so it serves as the org-wide default for all repositories.

## Audience

Both external open-source contributors and internal team members.

## Structure (Option A — Minimal reference doc)

1. **Getting Started** — two paths: external (fork) and internal (clone + branch)
2. **Branch Naming** — prefix table with examples
3. **Commit Messages** — `[TYPE] short description` format with examples
4. **Opening a PR** — base branch, description, request review

## Conventions

### Branch Naming
Prefix-based:
| Prefix | Use for |
|---|---|
| `feat/` | New features |
| `fix/` | General fixes |
| `hotfix/` | Urgent production fixes |
| `bugfix/` | Non-urgent bug fixes |
| `refactor/` | Code restructuring |
| `chore/` | Maintenance, deps, config |
| `docs/` | Documentation changes |

### Commit Messages
Format: `[TYPE] short description`

Types: `FEAT`, `FIX`, `HOTFIX`, `BUGFIX`, `REFACTOR`, `CHORE`, `DOCS`

### PR Requirements
Minimal — clear description, target `main`, request a review.

## Tone
Direct and concise. No filler. Code blocks for examples.
