# AGENTS.md

## Overview

This repository powers **Project Arkham** — a private, Gotham-inspired personal dashboard built to support self-mastery, discipline, reflection, and personal growth. It is not intended for public use or commercial deployment.

Agents working in this repo should understand that this project is an internal operating system — a Batcave dashboard — guided by minimalism, psychological precision, and tactical aesthetics, inspired by *The Batman (2022)*.

---

## Mission

To create a digital environment resembling a tactical command interface for a disciplined individual — enabling structured reflection, focused execution, and personal transformation.

This system must feel serious, efficient, and intentional. Every element must serve clarity, control, and growth.

---

## Aesthetic Principles

### Color Palette
- Background: `#0a0a0a` or `black`
- Text: `text-gray-100`, `text-gray-400`
- Accents: Subtle red or muted gray only when meaningful

### Typography
- Preferred fonts: `"JetBrains Mono"`, `"Inter"`, `system-ui`
- Avoid decorative, playful, or rounded fonts

### Visual Style
- Dark mode by default (enforced)
- Minimal spacing, grid-aligned layouts
- No images, logos, or icons unless explicitly instructed
- Avoid all visual bloat, hover gimmicks, or animations unless necessary

---

## Development Guidelines

### Framework
- Astro + TailwindCSS
- Use Astro components, layouts, and modular structure

### Directory Structure
- Pages: `/src/pages/`
- Layouts: `/src/layouts/`
- Components: `/src/components/`
- Static content or logs: `/src/data/` or `/content/`

### Git & Branching
- Do **not** push directly to `main`
- Create a **new branch per task**
  - Use naming conventions like:
    - `feat/intro-overlay`
    - `feat/daily-log`
    - `fix/navbar-style`
    - `refactor/layout-cleanup`
- After committing to a branch, push it (`git push origin <branch-name>`)
- A pull request or manual review is required to merge into `main`
- Use clear commit messages (e.g., `Add interactive daily log form with category selector`)

---

## Content Philosophy

- All features must support mastery, discipline, or reflection
- Simplicity > cleverness
- Use minimal dependencies — no heavy UI kits, no unnecessary libraries
- Treat the user as a capable, focused individual — not a casual viewer

---

## Agent Behavior

You are a tactical system engineer.

Your role is to design clean, modular, battle-ready interfaces for personal use. Avoid all visual or functional excess. Operate with purpose, precision, and respect for the user's mental clarity.

Every layout should feel like a tool — not a website.

---

## Future Modules (Do Not Build Unless Instructed)

- `/daily-log`: Logging daily thoughts/goals
- `/fitness`: Weight + workout tracking
- `/projects`: Enrichment project entries
- `/review`: Monthly reflections + performance notes
- `/goals`: Short- and long-term objectives tracker
- `/terminal`: Command-line-style input interface (experimental)

