# Regional Risk Register

**An integrated framework for regional risk intelligence, resilience governance, environmental risk assessment and investment decision-making.**

Independent public prototype · Version 0.1 · 13 October 2026

This repository contains a dependency-free static website and a source-attributed CERAC BCRA 2025 methodology reference, plus an **unvalidated scoping demonstrator for Rivierenland, the Netherlands**.

## Run and publish

- Open `index.html` directly in a browser, or serve this directory using any static web server (e.g. `python -m http.server 8000`).
- **GitHub Pages:** Repository Settings → Pages → Deploy from a branch → `main` → `/(root)`. Its initial URL will be `https://epemaster.github.io/regionalriskregister/`.
- **Cloudflare Pages:** Connect this GitHub repository, select a static/no-build project, build command empty, publish/output directory `/` (repository root). Connect `regionalriskregister.com` as a custom domain, using your domain registrar DNS instructions.
- Do not point DNS to both hosting providers. Choose one before changing records at Vimexx.

The repository includes no runtime dependencies, API credentials or tracking scripts. No personal data is collected by the application.

## Methodological provenance

CERAC's **Belgian Climate Risk Assessment (2025)** is a scientific-policy reference, **not a validation of Dutch regional risk**, an RRR endorsement, or an affiliation. The 28 imported source titles and Belgian 3°C-context urgency labels are reproduced as source metadata. Their local/Rivierenland severity, confidence, readiness and urgency remain **unassessed**.

- [BCRA overview](https://www.cerac.be/en/bcra)
- [BCRA published risk table](https://www.cerac.be/en/bcra#paragraph--273)
- [BCRA full report](https://www.cerac.be/sites/default/files/media/files/2026-08/cerac_bcra_rapport_final_v2_en_for_website.pdf) — notably pp. 22–29, 103–120, 143–145 and 162–169
- [BCRA methodological report](https://www.cerac.be/sites/default/files/media/files/2025-11/bcra_updated_methodological_report_final.pdf) — especially sections 1.5, 3, 4, 5 and 6

CERAC's 5-category urgency matrix is a **lookup** based on severity, scientific confidence and policy readiness, *not a multiplication of numeric ratings*. Its published national severity thresholds should **not** be directly applied to Dutch regions. Global Warming Levels +2/+3/+4°C refer to climate risk assessment; ecosystem-degradation risks were not separated into equivalent three levels. Cross-system dependencies in the initial BCRA were not fully quantified (methodological report §6).

The RRR extends this through explicit geographic scope, named risk ownership, evidence, scenario assumptions, inherent/current/residual states, dependency analysis, and conditional financeability. These are **independent proposed modules**, not CERAC methodology. The AMOC item is an **exploratory RRR scenario**, not a BCRA scored risk. Read the site's Source & integrity section.

## Repository structure

- `index.html` — the public framework website and interactive reference explorer
- `styles.css` — responsive design system
- `data.js` — 28 CERAC national source references and 8+1 proposed regional scoping items
- `app.js` — source explorer filters, evidence-status display and method lookup
- `README.md` — hosting and validation notes

## Scope and validation

The public site is a methodological prototype, not risk advice, a government assessment, an investment offer or quantified climate projections. Scientific references and observed local data must be independently reviewed before publishing regional risk ratings. Keep time horizon, global warming level and rate-of-change sensitivity separate.

For evidence intake, prioritise source provenance, licence, date, scale, uncertainty and documented reviewer approval. Validate regional geographic boundaries, Dutch governance responsibilities and financial claims before assigning confidence, priority or a financing mechanism.

## Hosting

Cloudflare Pages project: `regionalriskregister` (GitHub `main` branch). Preview address: https://regionalriskregister.pages.dev. The custom domain `regionalriskregister.com` is pending DNS and registrar verification.
