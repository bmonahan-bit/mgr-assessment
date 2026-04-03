# Mental Game Ratio (MGR) Assessment

**Paul Monahan Golf** — Play Better. Struggle Less. Enjoy More.

A 20-question mental game assessment that scores a golfer's 5 Heroes of Potential against their 5 Bandits to produce a Mental Game Ratio (MGR).

## How It Works

- 20 scenario-based questions, randomized each session
- Each question scored 1 (Never) to 5 (Always)
- Five Bandits scored (Fear, Frustration, Doubt, Shame, Quit) — A Total
- Five Heroes scored (Love, Acceptance, Commitment, Vulnerability, Grit) — B Total
- MGR = B Total / A Total
- Results include MGR gauge, per-concept breakdown, top Bandit strategy, and top Hero reinforcement

## 5 Heroes Framework

Each Hero directly counters a specific Bandit:

| Hero | Relationship | Bandit |
|------|-------------|--------|
| Love | conquers | Fear |
| Acceptance | eliminates | Frustration |
| Commitment | removes | Doubt |
| Vulnerability | prevents | Shame |
| Grit | beats | Quit |

## Features

- Email capture modal before results (with bypass option)
- Two Begin Assessment entry points on the launch page
- MGR gauge with High Interference / Battle / Low Interference zones
- mentalgolfbook.com CTA on results page (two placements)
- Fully responsive, single HTML file — no build step, no dependencies

## Result Tiers

| MGR | Tier |
|-----|------|
| Below 0.8 | High Interference |
| 0.8 – 1.2 | In the Battle |
| 1.2 – 1.8 | Building Momentum |
| 1.8+ | Playing With Freedom |

## Deployment

### Netlify (recommended)
1. Push to GitHub
2. Connect repo in Netlify dashboard
3. Build command: *(leave blank)*
4. Publish directory: `.`
5. Deploy

### Manual Netlify Drop
Drag the folder into [app.netlify.com/drop](https://app.netlify.com/drop)

## Files

| File | Purpose |
|------|---------|
| `index.html` | The full assessment app |
| `netlify.toml` | Netlify configuration and security headers |
| `.gitignore` | Git ignore rules |
| `README.md` | This file |

## Custom Domain
Set in Netlify: Site Settings > Domain Management > Add custom domain.
Suggested: `mgr.paulmonahan.com`

---

© 2025 Paul Monahan Golf. All Rights Reserved.
