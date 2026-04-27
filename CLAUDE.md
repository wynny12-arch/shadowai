# ShadowAI / Tactica Governance Gap — Claude Code Context

## Deploy workflow
`git add . && git commit -m "..." && git push origin main` → Vercel auto-deploys.
Remote: `https://github.com/wynny12-arch/shadowai.git` (main branch)

## What this is
Static HTML/JS tools for Tactica's AI governance and vibe coding content. Multiple standalone HTML files, no build step.

## Files
- `index.html` — "The Governance Gap" main page (Tactica branded)
- `vibe-coding-risk-check.html` — Vibe coding risk assessment tool
- `vibe-code-lab.html` — Vibe Code Lab overview page
- `vibe-code-lab-detail.html` — Detailed Vibe Code Lab content
- `tool-risk-database.json` — Risk data used by the risk check tool

## Stack
- Pure HTML/CSS/JS — no framework, no build step
- Static files served via Vercel
- `tool-risk-database.json` loaded client-side by the risk check tool

## Deploy notes
- No build step — what you edit is what gets deployed
- Changes to any HTML or JSON file are live after push
