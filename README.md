# Facu Villanueva — HR/AI Builder

**Live → [facuvillanueva.com.ar](https://facuvillanueva.com.ar)**

My obsession is simple: help build the best teams. I come from HR (5+ years running real recruitment operations) and I direct AI systems to build the tools that hiring and people teams actually need — specified, staged and verified, not demos.

This repo is the source of my personal site.

## What's on the site

| Project | Status | Link |
|---|---|---|
| **People** — full HRIS, real multi-tenant architecture | In build | — |
| **Applicant Tracking System** — multi-tenant, per-role pipeline customization | Active | [Live demo](https://recruiting-app-peopleos1.vercel.app/demo) |
| **Team Builder** — proposes role assignments optimizing fit *and* people's happiness; runs 100% in the browser | Free | [Use it](https://facuvillanueva.com.ar/team-builder) · [repo](https://github.com/villanuevafacundonicolas/team-builder) |
| **AI Governance Harness** — permission scoping, kill-switch, decision logs, rollback, promotion gates for autonomous agents | Open | [Fork it](https://github.com/villanuevafacundonicolas/claude-harness-template) |

## Stack

One static `index.html` — no framework, no build step, no tracking. EN/ES toggle built in. Deployed on Vercel; `vercel.json` only holds redirects (e.g. `/team-builder`).

```bash
# run locally: any static server works
npx serve .
```

## Contact

- Site: [facuvillanueva.com.ar](https://facuvillanueva.com.ar)
- LinkedIn: [facundo-nicolas-villanueva](https://www.linkedin.com/in/facundo-nicolas-villanueva/)
- Email: villanueva.facundo.nicolas@gmail.com
