# MATRIXX — AGENTS.md

> This file tells AI agents how to work with this repository.

## Repository Purpose

MATRIXX (Metrixcrm/Matrix) is the **ecosystem landing page** — the entry point for all MATRIXX products.

This repository hosts ONLY the `matrixxcrm.online` landing page. It is NOT a full application. It has no auth, no dashboard, no API.

## What This Repo Contains

- `index.html` — The MATRIXX ecosystem landing page (single-page, static)
- `README.md` — Product documentation

## Design System

The landing page uses the **MATRIXX Tools dashboard design tokens**:

- Font: Plus Jakarta Sans (headlines), JetBrains Mono (technical)
- Background: `#080c14` (dark)
- Surface: `#0f172a`
- Primary: `#06b6d4` (cyan)
- Text: `#f8fafc` / `#94a3b8`
- Border: `rgba(255, 255, 255, 0.1)`

See https://github.com/bunnyexchange35-afk/Tools for the full design system reference.

## Subdomains

| Product | Domain | Repo |
|---------|--------|------|
| Tools | tools.matrixxcrm.online | Metrixcrm/Tools |
| Merchants | merchants.matrixxcrm.online | Metrixcrm/Merchants |
| Dating | dating.matrixxcrm.online | Metrixcrm/Dating |
| Store | store.matrixxcrm.online | Metrixcrm/Store |

## Rules

1. **DO NOT add auth** — this is a public landing page
2. **DO NOT add dashboards or API routes** — this repo is for the landing page only
3. **DO NOT embed other apps** — link to them via https
4. **DO NOT add fake stats** — no user counts, tool counts, ratings
5. **DO keep design consistent** with Tools dashboard design tokens
6. **DO use responsive design** — mobile-first
7. **DO keep it lightweight** — no frameworks, no build step needed
