# SaathEra

**Meet intentionally. Focus mutually. Grow privately.**

Verified relationship journey platform for India — curated discovery, safe meetings, mutual Focus Mode, enforced Together Mode, and a private couple space.

- **Repository:** https://github.com/WenliceRepo/SaathEra
- **Prepared by:** WenLice
- **Launch market:** Delhi NCR (Noida, Gurugram, selected Delhi zones)

## Product promise

When you choose each other, SaathEra stops showing you anyone else.

## Stack (confirmed)

| Layer | Technology |
|-------|------------|
| Mobile | React Native + Expo + TypeScript |
| Public web | Next.js App Router |
| Admin | Next.js (separate app) |
| Backend | NestJS modular monolith |
| Database | PostgreSQL |
| Monorepo | pnpm + Turborepo |

## Build order

**Website first** — public site + admin portal for concierge pilot, then mobile app.

See [docs/BUILD-ORDER.md](docs/BUILD-ORDER.md).

## Design

Figma preparation guide and design tokens:

- [docs/design/FIGMA-BRIEF.md](docs/design/FIGMA-BRIEF.md)
- [docs/design/design-tokens.json](docs/design/design-tokens.json)
- [docs/design/copy-deck.md](docs/design/copy-deck.md)

## Repo structure (planned)

```
SaathEra/
├── apps/
│   ├── public-web/     # Marketing, apply, safety, legal
│   ├── admin-web/      # Verification, cohort, safety ops
│   ├── mobile/         # RN + Expo (later)
│   └── api/            # NestJS (later)
├── packages/
│   └── design-tokens/
└── docs/
```

## Getting started (local)

```bash
git clone https://github.com/WenliceRepo/SaathEra.git
cd SaathEra
```

Push first commit (after Git is installed):

```bash
git init
git remote add origin https://github.com/WenliceRepo/SaathEra.git
git add .
git commit -m "Initial project scaffold: docs, design tokens, Figma brief"
git branch -M main
git push -u origin main
```

## License

Proprietary — WenLice / SaathEra. All rights reserved.
