# FansAI · Global Footprint Dashboard

**Live demo →** https://fansai-dashboard.vercel.app/

AI-native content science company · Overseas business map demo.

A single-file interactive dashboard featuring:

- **3D globe** (globe.gl + Three.js) with hex-polygon country topology, animated arcs, and pulsing strategic-market rings
- **Tactile Digital / Aurora UI** design system with museum-gallery palette (ochre, terracotta, sage, indigo on warm ink)
- **10 markets** across 3 tiers (Strategic / Active / Emerging) — US · UK · DE · JP · CN · KR · BR · AE · CA · SG
- **Trending Board** — flagship cases ranked by heat score (TCL Olympics, Momcozy × Home Alone, F1×Disney×Miniso, etc.)
- **Per-market localized client reviews** — 8 testimonials per market, 4 pages × 3 cards auto-rotating every 5s
- **Per-market localized honors** — Cannes Lions, D&AD, ACC Tokyo, Spikes Asia, Dubai Lynx, SIFF/BJIFF, etc.
- **Origin language toggle** — every signal supports EN / 中 / ORI (native: 日本語 / Français / Deutsch / Português / 한국어) per-card
- **Country dropdown** mounted on the country detail card (lower-left) with search + tier-grouped list
- **EN / 中 bilingual** chrome with synchronized state across all components

## Stack

Pure single-file `index.html` — no build step, no framework. Just open in browser.

CDN dependencies (auto-loaded):
- `three@0.149.0` — WebGL rendering
- `globe.gl@2.27.2` — globe widget
- `world-atlas` + `natural-earth` GeoJSON — country topology

## Deploy

Drop `index.html` on any static host. Auto-deployed to Vercel.
