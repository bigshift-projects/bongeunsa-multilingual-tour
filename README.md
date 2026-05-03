# Bongeunsa Multilingual Tour Static Package

This repository is a static Vercel deployment package for Dealcatch proposal artifacts.

## Routes

- `/`: UX screen preview (`index.html`)
- `/proposal.pdf`: proposal PDF download
- `/proposal`: proposal PDF download alias
- `/portfolio.pdf`: BigShift portfolio PDF
- `/portfolio`: BigShift portfolio PDF alias

## Vercel Setup

1. In the Vercel dashboard, choose Add New... > Project.
2. Import this GitHub repository.
3. Set Framework Preset to Other, or keep the auto-detected value.
4. Keep Root Directory as the repository root.
5. Leave Build Command empty.
6. Leave Output Directory empty.
7. Click Deploy.

Codex only uploads the static package to GitHub. Vercel import and the actual deployment must be completed manually in Vercel.
