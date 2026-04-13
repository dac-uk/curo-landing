# Eyrie Landing Page

Marketing website for Eyrie — the privacy-first personal finance app for iOS.

**Live:** Deployed via GitHub Pages on push to `main`

> Related repos: [curo-ios](https://github.com/dac-uk/curo-ios) (iOS app) | [curo-backend](https://github.com/dac-uk/curo-backend) (Vapor API) | [CuroBusiness](https://github.com/dac-uk/CuroBusiness) (web dashboard)

## Overview

Static single-page marketing site showcasing Eyrie's features and driving App Store downloads. No build tools or frameworks — pure HTML and CSS.

## Features Promoted

- Morning briefings and daily financial summaries
- Smart bill tracking with price change alerts
- Anomaly detection for unusual transactions
- Natural language queries ("Ask Eyrie")
- Open Banking integration (UK banks via Yapily)
- Privacy-first architecture (bank-grade security, on-device processing)
- Financial Decision Engine (mortgage, pension, tax optimisation)

## Stack

- **HTML/CSS** — no build step, no JavaScript framework
- **Fonts:** Inter + JetBrains Mono (Google Fonts)
- **Design:** Dark theme with owl gold (`#C9A84C`) accent, matching the iOS app's design system
- **Deployment:** GitHub Actions → GitHub Pages (auto-deploy on push to `main`)

## Structure

```
├── index.html              # Complete landing page (HTML + inline CSS)
├── assets/
│   └── favicon.svg         # Eyrie favicon
├── copy/
│   └── app-store-listing.md    # App Store metadata and marketing copy
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Pages deployment workflow
```

## Local Development

```bash
# Just open in a browser — no build step needed
open index.html
```

## Deployment

Pushes to `main` automatically deploy to GitHub Pages via the workflow in `.github/workflows/deploy.yml`.
