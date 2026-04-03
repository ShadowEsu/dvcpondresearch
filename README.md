# DVC Pond Research

Website for the **Diablo Valley College (DVC) Pond Research** project—a **MESA**-run research program studying pond habitats on campus and how we can make them more habitable for the organisms that live there.

The public site will document field work, methods, and findings across campus pond sites, in a tone that fits real research: clear, evidence-based, and accessible—not a generic club page.

---

## Bio team

Brenda, Ariel, Ishak, Rita, and Preston.

---

## Purpose

- Present the program as a **legitimate research effort** through MESA.
- Share **what we study**, **how we study it**, and **what we have learned**.
- Make **results and discoveries** easy to browse (by pond, topic, or time).
- Explain **why habitat quality matters** for organisms in and around each pond.

---

## Audience

- DVC students and faculty who want context or might get involved.
- Visitors who care about pond health and student research without heavy jargon.
- A stable place to archive figures, summaries, and links to deeper work over time.

---

## Scope: ponds under study

We compare and track **five pond sites**: **Pond 0 through Pond 4**. Each pond page should eventually include:

| Topic | What to cover |
|--------|----------------|
| **Location / context** | How this pond fits the campus or study design (brief). |
| **Habitat focus** | What “more habitable” means here—water quality, structure, plants, wildlife. |
| **What we measure** | Parameters and methods in plain language (+ optional technical detail). |
| **Results** | Tables, charts, or narrative summaries as we produce them. |
| **Discoveries & notes** | Observations, seasonal changes, open questions. |

Separate pages can compare **across ponds** (e.g., which site stands out for a given indicator).

---

## Planned site structure (draft)

| Section | Goal |
|--------|------|
| **Home** | Mission, MESA + DVC context, links to ponds and latest updates. |
| **About the program** | MESA partnership, goals, safety/ethics, participation (if applicable). |
| **Ponds** | Hub for Pond 0–4; each pond has its own page. |
| **Results & discoveries** | Dated entries; optional filters by pond/tag later. |
| **Methods / tools** | Sampling or observation, equipment, reproducibility in plain language. |
| **Resources** | DVC/MESA links, readings, data downloads if we publish any. |
| **Contact** | Advisor / team contact. |

Route names can follow your stack (e.g. `/ponds/0` vs `/pond-0`).

---

## Content to prepare

- Short **program blurb** and optional **hero** image or illustration.
- Per pond: **1–2 paragraphs** of stable text plus room for **figures** (photos, graphs).
- A rhythm for **updates**—even a monthly “lab notebook” style post keeps the site alive.

---

## Design direction

- **Research-first:** readable type, whitespace, figures with captions.
- **Nature + lab:** greens, blues, warm neutrals; avoid loud stock looks.
- **Fonts:** [`styles/fonts.css`](./styles/fonts.css) loads Google Fonts as CSS variables—pick one heading + one body pairing and stay consistent.

---

## Technical next steps

1. Choose a **stack** (static HTML/CSS, or e.g. Astro, Next, Vite + React).
2. **Import** [`styles/fonts.css`](./styles/fonts.css) in global CSS or layout once.
3. Build a **layout shell**: header, footer, main content, reusable pond template.
4. **Add content** over time; use “coming soon” only where needed.
5. **Optional:** analytics, RSS, or a simple CMS later.

---

## Success criteria

- A new visitor can explain **what we study** and **why ponds 0–4** after the home page and one pond page.
- Results and discoveries are **easy to find** without hunting through unrelated pages.
- The site stays **easy to extend** as new semesters add data.

---

## Open questions

- **Faculty / MESA** contact for approving public copy?
- Publish **raw data** or **summaries only**?
- Need **bilingual** content or formal **accessibility (WCAG)** review?

---

## Repository

| Item | Description |
|------|-------------|
| [`styles/fonts.css`](./styles/fonts.css) | Google Fonts and CSS variables |
| [`PLAN.md`](./PLAN.md) | Full website plan (same topics as below, in one doc) |

*Planning summary last aligned with PLAN.md: April 2026.*
