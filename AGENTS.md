# AGENTS.md

## Overview  
This repository powers **Project Arkham** — a private, Gotham-inspired personal dashboard designed for self-mastery, discipline, reflection, and personal growth.  
It is not intended for public use or commercial deployment.

Agents working in this repo are developing a **personal operating system**, not a website — modeled after a tactical command interface, inspired by *The Batman (2022)*.

---

## Mission  
Create an environment that feels like a **digital Batcave** — a serious, minimal, functional system where the user operates with clarity and intention.

Every line of code must serve **presence**, **utility**, and **transformation**.

---

## Aesthetic Principles

### Color Palette
- Background: `#0a0a0a` or `black`
- Text: `text-gray-100`, `text-gray-400`
- Accents: Muted red or gray (only when meaningful)

### Typography
- Preferred fonts: `"JetBrains Mono"`, `"Inter"`, `system-ui`
- Avoid decorative, rounded, or playful fonts

### Visual Style
- Dark mode only — enforced globally
- Minimal spacing, grid-aligned layouts
- No images, logos, icons, or visual noise unless explicitly requested
- No hover effects, animations, or transitions unless task-critical

---

## Development Guidelines

### Framework & Stack
- Astro for frontend rendering
- TailwindCSS for styling
- LocalStorage for storing logs (unless otherwise directed)
- Minimal dependencies — no UI kits or external libraries unless approved

### Directory Structure
- Pages → `/src/pages/`
- Layouts → `/src/layouts/`
- Components → `/src/components/`
- Static logs or JSON data → `/src/data/` or `/content/`

---

## Shared File Rules

Only update these files when the task **specifically requires it**:
- `/src/pages/index.astro`
- `/src/components/Navbar.astro`
- `tailwind.config.js`
- `global.css`

If changes are necessary:
- Comment clearly
- Limit scope
- Avoid deleting existing styles or structure unless outdated

---

## Git & Branching Protocol

### ✅ All agent work must be done in: `feat/new`

- Never push directly to `main`
- Never create new branches
- Use only the shared `feat/new` branch for all updates

### Working Instructions

1. **Pull the latest main:**
   ```bash
   git checkout feat/new
   git pull origin main
Push your updates:

bash
Copy
Edit
git add .
git commit -m "Describe the task completed"
git push origin feat/new
Pull requests must originate from feat/new

One open PR at a time from feat/new → main

PR titles should follow: Add [feature], Fix [issue], Refactor [module]

Content Philosophy
Every feature must support:

Mastery

Discipline

Reflection

Do not build for decoration — build for focus.
Simplicity > cleverness
Every page must feel like a tool.

Agent Behavior
You are a tactical system engineer.

You build serious, functional interfaces that operate like command-line utilities — modular, precise, and quiet unless called.

No wasted movement.
No visual noise.
Think Arkham. Think control. Think clarity.




