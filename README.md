# Horizon Funnel

A single-page workbench for systematic innovation of products, processes, and services — capture ideas, run them through structured GenAI ideation prompts, classify by growth horizon and readiness level, score them, and shortlist what actually gets resourced.

Open [`index.html`](index.html) directly in a browser, or enable GitHub Pages on this repo (Settings → Pages → deploy from `main`) to host it live. No build step, no dependencies, no backend — everything runs client-side and persists to the browser's `localStorage`.

## What it does

- **Intake** — capture an idea's title, type (product/process/service), problem statement, and description.
- **Ideation assist** — generates a ready-to-paste GenAI prompt per idea, using one of five divergent techniques: SCAMPER, TRIZ contradiction analysis, Jobs-to-be-Done, first-principles, or analogical transfer/biomimicry.
- **Horizon classification** — McKinsey's Three Horizons (H1 core, H2 adjacent, H3 transformational).
- **Readiness scale** — a 1–9 scale adapted from NASA/DoD Technology Readiness Levels, generalized beyond hardware to cover processes and services.
- **Funnel scoring** — a weighted composite of desirability, feasibility, viability, and strategic fit (0–100).
- **Stage-gate board** — Discover → Define → Develop → Validate → Scale, as a kanban view.
- **Portfolio matrix** — a Horizon × TRL bubble chart that exposes whether the pipeline is overloaded with safe, low-TRL H1 bets or missing H3 options entirely.
- **Shortlist gate** — a single adjustable threshold that turns the full idea list into a resourceable few.
- **Playbook** — the frameworks above, plus the courses that informed them, documented in-app.

## Frameworks and sources

- McKinsey's Three Horizons of Growth (Baghai, Coley & White, *The Alchemy of Growth*, 1999)
- NASA/DoD Technology Readiness Levels (adapted here for non-hardware use)
- IDEO's Desirability/Feasibility/Viability lenses
- Stage-Gate process (Cooper)
- SCAMPER, TRIZ, Jobs-to-be-Done, first-principles, analogical transfer

Curriculum references: MIT Sloan Executive Education's *Systematic Innovation of Products, Processes, and Services*, MIT Professional Education's *Product Innovation in the Age of AI* and *Breakthrough Innovation: Harnessing AI*, MIT xPRO's *Technology & Innovation Acceleration Program*, and Harvard Business School Online's *Design Thinking and Innovation*.

## Data and privacy

All idea data lives in your browser's `localStorage` only — nothing is sent to a server. Use the Export/Import backup buttons in the footer to move data between browsers or back it up as JSON.
