# profile/README.md Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Create `profile/README.md` to serve as Kausora Technologies' public GitHub org profile page.

**Architecture:** Single markdown file at `profile/README.md`. GitHub renders this automatically at github.com/KausoraTechnologies. Four sections: heading, intro paragraph, capability list, contact links.

**Tech Stack:** Markdown

---

### Task 1: Write profile/README.md

**Files:**
- Create: `profile/README.md`

**Step 1: Create the `profile/` directory and file with exactly this content**

```markdown
# Kausora Technologies

Kausora Technologies is an AI, robotics, and automation company headquartered in Abu Dhabi, UAE and Sheffield, UK. We help organisations scale faster and operate more efficiently through intelligent software, industrial systems, and data-driven solutions.

## What We Build

- AI & agentic workflow automation
- Industrial robotics & autonomous systems
- Predictive analytics & data intelligence
- Digital twin & simulation
- Cloud infrastructure
- Custom software development
- Odoo business management (ERP/CRM)

## Get in Touch

- Website: [www.kausora.com](https://www.kausora.com)
- Email: [contact@kausora.com](mailto:contact@kausora.com)
```

**Step 2: Commit**

```bash
git add profile/README.md
git commit -m "[DOCS] Add org profile README"
```
