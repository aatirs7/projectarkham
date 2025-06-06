# AGENTS.md

## Overview

This repository powers **Project Arkham** — a private, Gotham-inspired personal dashboard designed for self-mastery, discipline, reflection, and personal growth. It is not intended for public use or commercial deployment.

Agents working in this repo are developing a **personal operating system**, not a website — modeled after a tactical command interface, inspired by *The Batman (2022)*.

---

## Mission

Create an environment that feels like a digital Batcave — a serious, minimal, functional system where the user operates with clarity and intention.

Every line of code must serve presence, utility, and transformation.

---

## Aesthetic Principles

### Color Palette
- **Background**: `#0a0a0a` or black
- **Text**: `text-gray-100`, `text-gray-400`
- **Accents**: Muted red or gray (only when necessary or meaningful)

### Typography
- Preferred fonts: `"JetBrains Mono"`, `"Inter"`, `system-ui`
- No decorative, rounded, or playful fonts

### Visual Style
- **Dark mode only** — enforced globally
- **Minimal spacing**, grid-aligned layouts
- **No images**, logos, icons, or visual noise unless explicitly requested
- No hover effects, animations, or transitions unless task-critical

---

## Development Guidelines

### Framework & Stack
- **Astro** for frontend rendering
- **TailwindCSS** for styling
- **LocalStorage** for storing logs (unless otherwise directed)
- Keep dependencies minimal — no UI kits or external libraries unless approved

### Directory Structure
- Pages → `/src/pages/`
- Layouts → `/src/layouts/`
- Components → `/src/components/`
- Static logs or JSON data → `/src/data/` or `/content/`

### Shared File Rules
> **Only update these files when the task specifically requires it.**
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

### ❌ Never push directly to `main`

### ✅ Always follow this workflow:
1. Pull latest main:
   ```bash
   git checkout main
   git pull origin main
Create a new branch:

bash
Copy
Edit
git checkout -b feat/<task-name>
🧠 Branch Naming Conventions
feat/<feature> — e.g., feat/daily-log-page

fix/<bug> — e.g., fix/navbar-spacing

refactor/<target> — e.g., refactor/index-layout

🛑 Pull Request Requirements
Push only task-related files

Never touch unrelated layouts, configs, or pages

Use clear commit messages, e.g.:

Add responsive daily log page with textarea

Refactor navbar to support flex-wrap

A manual review or PR must be approved before merging

Content Philosophy
Everything should serve:

Mastery

Discipline

Reflection

Do not build for “design” — build for focus

Simplicity > cleverness

Every page must feel like a tool

Agent Behavior
You are a tactical system engineer.

You build serious, functional interfaces that operate like command-line utilities — modular, precise, silent unless called.

No wasted movement. No visual noise. Think Arkham. Think control. Think clarity.

File Ownership Summary
File	Rules
index.astro	Do not modify unless the task specifies homepage changes
Navbar.astro	Edit only when instructed; preserve current layout
global.css, tailwind.config.js	Only modify for font, spacing, or dark mode tasks
Shared Layouts / BaseLayout	Extend only via components unless layout task is assigned

Future Modules (For Reference — Do Not Build Unless Instructed)
/daily-log — Log daily reflections & thoughts

/fitness — Log workouts, track weight

/projects — Archive enrichment projects

/review — Monthly or weekly reflections

/goals — Short-/long-term objective tracker

/terminal — Experimental CLI-like interface for logging & querying

Status
You are not building a portfolio. You are constructing a system to forge discipline.

Work clean. Push with purpose. Operate like you're being watched by Batman himself.
