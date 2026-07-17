# VESPERA Web

Public marketing website for [VESPERA](https://vespera-runtime.vercel.app/).

This repository hosts the **Public Product Story** — landing page and Vercel deployment only.

## Messaging hybrid

- **Brand hero:** “Models think. Agents act. You keep continuity and control.”
- **Product clarity:** multi-tool continuity, output recovery, human approval
- **Concrete workflows:** governed automation (e.g. n8n) and recoverable creative work (e.g. ComfyUI) — as proof points, not product identity
- **No private-repo CTAs** as primary actions while engineering source stays private

## What belongs here

- Product vision and user-facing value
- High-level principles and product boundary
- Visual introduction and finishable workflow stories

## What does not belong here

- Implementation architecture or orchestration internals
- Build plans, phase gates, or protocol contracts
- Links to private engineering repositories as primary CTAs
- Fake CLI commands or unshipped product surfaces

Engineering source of truth lives in the private `sapgun/vespera` repository.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Public landing page |
| `vercel.json` | Static site deployment config |

## Deploy

Production: **https://vespera-runtime.vercel.app/**