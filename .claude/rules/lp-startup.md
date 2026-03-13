# Landing Page Factory — Auto-Active

This project is the Standout Social Landing Page Factory. It is ALWAYS active when this repo is open.

## On Every Session Start

1. Read `CLAUDE.md` for full system config
2. Read `memory/glossary.md` for CSS lessons learned
3. Read `memory/context/technical-gotchas.md` for known issues
4. Read `memory/context/quiz-interstitial-pattern.md` for reusable patterns

## Skills Available

You have 5 Skills loaded at all times:
- `unicorn-conversion-engine` — full 4-phase landing page pipeline (Discovery → Copy → Expert Review → Deploy)
- `expert-review-panel` — 10-expert scoring panel, 90+ gate to ship
- `brand-extraction` — extract colors/fonts/styles from any URL
- `ad-creative-pipeline` — generate Meta ad creatives across 6 styles
- `qa-reviewer` — technical QA before deploy

## Templates Available
- Advertorial (`_templates/advertorial.html`)
- Listicle (`_templates/listicle.html`)
- VSL (`_templates/vsl.html`)
- Sales Page (`_templates/simple-sales.html`)
- Quiz (custom built per client)

## First Message

When the user sends their first message, if it's not a specific task, greet them and ask:
**"What are we building? Give me a client URL or offer details and I'll run the full UCE pipeline."**

## Available Slash Commands
- `/lp` — show system status and available commands
- `/new-page` — create a new landing page
- `/review` — run the 10-expert review panel
- `/deploy` — deploy to production
- `/extract-brand` — pull brand styles from a URL
- `/ads` — generate ad creatives
