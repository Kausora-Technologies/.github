# CONTRIBUTING.md Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Create a minimal, scannable `CONTRIBUTING.md` at the repo root that serves as the org-wide default for all Kausora Technologies repositories.

**Architecture:** Single markdown file at the repo root. No code, no tests. Four sections: Getting Started, Branch Naming, Commit Messages, Opening a PR.

**Tech Stack:** Markdown

---

### Task 1: Write CONTRIBUTING.md

**Files:**
- Create: `CONTRIBUTING.md`

**Step 1: Create the file with the following content**

```markdown
# Contributing to Kausora Technologies

Thanks for contributing! Please follow the guidelines below.

---

## Getting Started

**External contributors**
1. Fork the repository
2. Create a branch from `main` using the naming convention below
3. Make your changes and open a pull request

**Internal contributors**
1. Clone the repository
2. Create a branch from `main` using the naming convention below
3. Make your changes and open a pull request

---

## Branch Naming

Use the appropriate prefix followed by a short description:

| Prefix | Use for |
|---|---|
| `feat/` | New features |
| `fix/` | General fixes |
| `hotfix/` | Urgent production fixes |
| `bugfix/` | Non-urgent bug fixes |
| `refactor/` | Code restructuring |
| `chore/` | Maintenance, dependencies, config |
| `docs/` | Documentation changes |

**Examples:**
```
feat/add-user-auth
bugfix/fix-null-pointer
docs/update-readme
```

---

## Commit Messages

Format: `[TYPE] short description`

**Types:** `FEAT`, `FIX`, `HOTFIX`, `BUGFIX`, `REFACTOR`, `CHORE`, `DOCS`

**Examples:**
```
[FEAT] Add user authentication
[BUGFIX] Fix null pointer in login flow
[DOCS] Update contributing guidelines
[CHORE] Bump dependencies
```

---

## Opening a PR

- Target the `main` branch
- Write a clear description of what the PR does and why
- Request a review from a maintainer
```

**Step 2: Commit**

```bash
git add CONTRIBUTING.md
git commit -m "[DOCS] Add org-wide CONTRIBUTING.md"
```
