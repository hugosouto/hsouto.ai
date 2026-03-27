# CLAUDE.md — hsouto.ai

## Project Overview

Personal website for **Hugo Souto** at `hsouto.ai`. This is Hugo's professional identity — the architect behind the systems, the advisor behind the practice, the mind behind **4io.ai**.

## Brand Positioning

Hugo is not selling himself. He already builds AI systems governments trust to serve 170 million citizens. The site exists for people who already know his name — or should.

**Voice**: Authoritative. Understated. The confidence of someone whose work speaks. Think Gartner Fellow bio, not freelancer portfolio.

**Core statement**: "I build AI systems governments trust to serve 170 million citizens. I advise organizations ready for the same standard."

**What this site is NOT**:
- A job application ("here's why you should hire me")
- A service menu ("what you get")
- A proof-stack ("here's why I'm credible")

**What this site IS**:
- A presence. Selected work. The practice. Contact.
- Elegant, minimal, authoritative.

## The Two Brands

| | hsouto.ai | 4io.ai |
|---|---|---|
| **What** | Hugo the person. The advisor. The architect. | The factory. Products, tools, frameworks. |
| **Tone** | Personal authority. Selective. | Product-oriented. Capability showcase. |
| **Content** | Bio, selected work, practice overview, contact | Products, demos, frameworks, pricing |
| **Relationship** | Hugo's face, Hugo's name, Hugo's reputation | The vehicle. The practice's output arm. |

They reinforce each other. hsouto.ai establishes the person; 4io.ai shows what the practice produces.

## Site Structure

1. **Hero (dark)** — Name. One sentence. Three metrics. No subtitle list, no typewriter, no tagline clutter.
2. **Selected Work** — Carousel of 5 projects. Expandable details. Reframed from "proof" to "portfolio" — these are things Hugo built, not evidence he can build.
3. **The Practice** — hsouto.ai (advisory) + 4io.ai (products) + Training + Industry recognition. This is the unified offering.
4. **Technical Depth** — Tech stack in pill grid. Compact. For people who care.
5. **Contact (dark)** — "Select engagements. Serious problems." Email, LinkedIn, GitHub, 4io.ai.
6. **Evidence** — Reference links to live systems. Compact. No explanations needed.

## Content Principles

- **State, don't sell.** "$630M saved" not "I can save you money."
- **Fewer metrics, more weight.** Three hero metrics ($29M, $630M, 13 yrs), not eight competing numbers.
- **No "For clients:" boxes.** The whole site is for clients. No need to label it.
- **No "generous with initial conversations."** That's needy. "Select engagements. Serious problems." is the energy.
- **Details on demand.** Expandable STAR stories for those who want depth. Surface is clean.
- **4io.ai is elevated**, not just a footer link. It's part of "The Practice" section alongside Hugo's advisory work.

## Key Metrics (source of truth)

Use these exact figures. Don't inflate. Don't stack all of them in one place.

**Hero metrics** (the big three):
- **$29M** — AI contract portfolio under technical governance
- **$630M** — Public funds saved through AI systems Hugo built
- **13 years** — Government technology (7 in AI/ML)

**Case study metrics** (inside carousel):
- **355K+** conversations — Chat GOV.BR since Jan 2026
- **$13M+** contract — Chat GOV.BR
- **$4.4M** allocation — ComprasGov InSights / PBIA
- **254K+** procurement processes — ALICE
- **National Treasury Prize 2024** + **Best Innovation in Procurement 2026** (Prêmio 19 de Março, 21st Brazilian Congress of Public Procurement) — ALICE
- **$4.3B** tracked — COVID Dashboard
- **46+** institutions — CLAD Costa Rica
- **28 days** — COVID Dashboard build time

**Supporting** (inside Practice section):
- **150+** executives trained at Gerdau
- **Huawei AI Judge 2025**
- **World Bank fellowship endorsed**
- **4 Bigtech vendors** benchmarked (Huawei, AWS, Google, Salesforce)
- **4 DS/ML Engineers** on Hugo's team

## Design System

- **Fonts**: IBM Plex Sans (body), IBM Plex Mono (accents). Non-negotiable.
- **Palette**: Navy (#1A2744), Blue (#0057B8), Gold (#B8860B), Green (#15803D). Light sections alternate with dark gradient.
- **Layout**: Vertical snap-scroll. Progress rail (right). Language toggle (bottom-left).
- **Motion**: Fade-in on scroll. Hover lifts on cards. That's it.
- **Tone**: Dark hero, light work, light practice, light tech, dark contact. Alternating gives rhythm.

## File Structure

```
hsouto.ai/
├── CLAUDE.md          # This file
├── index.html         # Single-page site
├── favicon.png
└── README.md
```

## Domain & Deployment
- **Domain**: hsouto.ai
- **Hosting**: Cloudflare Pages
- **Old domain**: hsouto.co → redirect to hsouto.ai

## Editing Guidelines

- When updating metrics, update both the HTML and this CLAUDE.md.
- Case studies are ordered by impact (Chat GOV.BR first), not chronology.
- Never add "For clients:" callout boxes. The site speaks to clients by default.
- Keep the hero to 3 metrics max. More dilutes authority.
- 4io.ai link appears in two places: Practice section and Contact cards. That's enough.
- Bilingual (EN/PT) for every text element. English is default.
