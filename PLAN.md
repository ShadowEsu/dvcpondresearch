# DVC Pond Research — Website Plan

A public-facing site for the **DVC MESA Pond Research** program: documenting field work, methods, and findings across the campus pond sites, with a tone that matches real research communication (clear, evidence-based, accessible).

---

## Purpose

- Present the program as a **legitimate research effort** run through MESA, not a generic club page.
- Share **what we study**, **how we study it**, and **what we have learned** so far.
- Make **results and discoveries** easy to browse (by pond, by topic, or by time).
- Explain **why habitat quality matters** for the organisms living in and around each pond.

---

## Audience

- DVC students and faculty considering involvement or using the site for context.
- Visitors who want to understand pond health and student research without jargon walls.
- Future you: a stable place to archive figures, summaries, and links to deeper work.

---

## Scope: Ponds Under Study

The program compares and tracks **five pond sites**, labeled **Pond 0 through Pond 4** (five distinct bodies of water). Each pond page should cover:

- **Location / context** — how this pond fits the campus or study design (brief).
- **Habitat focus** — what “more habitable” means here (e.g., water quality indicators, structure, surrounding vegetation, visible wildlife).
- **What we measure** — parameters and methods in plain language (and optional technical detail).
- **Results** — tables, charts, or narrative summaries as the program produces them.
- **Discoveries & notes** — interesting observations, seasonal changes, open questions.

Cross-cutting pages can summarize **comparisons across ponds** (e.g., which site shows the strongest signal for a given indicator).

---

## Site Map (draft)

| Section | Goal |
|--------|------|
| **Home** | Mission, MESA + DVC context, quick links to ponds and latest updates. |
| **About the program** | MESA partnership, research goals, safety/ethics, how to participate (if applicable). |
| **Ponds** | Hub with cards or list for Pond 0–4; each pond has its own subpage. |
| **Results & discoveries** | Blog-style or dated entries, filterable by pond and tag (optional later). |
| **Methods / tools** | How sampling or observation works; equipment; reproducibility in student-friendly terms. |
| **Resources** | Links to DVC/MESA, readings, data downloads (if you publish any). |
| **Contact** | Email or form placeholder for advisors / team. |

Adjust names to match your stack (e.g., `/ponds/0` vs `/pond-0`).

---

## Content You Will Need

- Short **program blurb** and one **hero image** or illustration per release (optional).
- For each pond: **1–2 paragraphs** of stable text + room for **figures** (photos, graphs).
- A rhythm for **updates**: even a monthly “lab notebook” style post is enough to keep the site alive.

---

## Design Direction (non-binding)

- **Research-first**: readable typography, generous whitespace, figures with captions.
- **Nature + lab**: greens/blues/warm neutrals; avoid neon or gimmicky stock imagery.
- **Fonts**: see `styles/fonts.css` — Google Fonts are loaded and exposed as CSS variables; pick one heading + one body pairing and stay consistent.

---

## Technical Next Steps

1. **Choose a stack** — static HTML/CSS, or a framework (e.g., Astro, Next, Vite + React) if you want components and fast iteration.
2. **Wire `styles/fonts.css`** into your global stylesheet or layout (one import).
3. **Build layout shell** — header, footer, main content, pond template.
4. **Add real content** incrementally; ship with “coming soon” blocks only where necessary.
5. **Optional**: analytics, RSS for updates, or a simple CMS later.

---

## Success Criteria

- Someone unfamiliar with the project can explain **what you study** and **why ponds 0–4** after skimming the home and one pond page.
- Results and discoveries are **findable** without digging through unrelated pages.
- The site remains **easy to extend** as new semesters add data.

---

## Open Questions (fill in as you go)

- Who is the **faculty / MESA** contact for public-facing copy approval?
- Will you publish **raw data** or only summaries?
- Do you need **bilingual** content or accessibility audits (WCAG) as a formal requirement?

---

*Last updated: April 2026*
