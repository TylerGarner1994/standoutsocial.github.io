# Standout Social — Landing Page Factory

## CRITICAL: Campaign State First
**Before creating ANY content**, check if campaign_brief.md exists in the project. If it does, read it FIRST. This is your ground truth.

## Core Philosophy
Standout Social builds high-converting landing pages, ads, and marketing funnels. Every output must be:
- **Direct response first**: Every element earns its place by driving conversion
- **Brand-authentic**: Matches client voice, not generic marketing speak  
- **Evidence-backed**: Real results, specific numbers, named clients
- **Strategically sound**: Right message, right audience, right moment

## Workspace Structure
```
/project-root/
├── campaign_brief.md      # ALWAYS check this first if it exists
├── CLAUDE.md              # This file
├── .claude/
│   └── skills/            # Specialized skill modules
│       ├── ad-creative-pipeline/
│       ├── advertorial-architect/
│       ├── ai-seo-intelligence/
│       ├── brand-extraction/
│       ├── brand-style-extractor/
│       ├── competitive-intelligence/
│       ├── conversion-copy-architect/
│       ├── dr-market-research/
│       ├── expert-review-panel/
│       ├── legendary-sales-letter/
│       ├── listicle-architect/
│       ├── meta-image-ad-generator/
│       ├── meta-video-ads/
│       ├── persona-architect/
│       ├── qa-reviewer/
│       ├── quiz-funnel-architect/
│       ├── unicorn-ad-creative-engine/
│       ├── unicorn-conversion-engine/
│       └── vsl-master-architect/
└── output/                # All generated content goes here
```

## Available Skills & When to Use Them

### Research & Strategy
- **dr-market-research** → Deep market research, competitor analysis, customer psychology
- **persona-architect** → Build detailed customer avatars from research
- **competitive-intelligence** → Analyze competitor positioning and messaging
- **brand-style-extractor** → Extract brand voice, style, tone from existing materials
- **brand-extraction** → Quick brand voice capture from website/content

### Ad Creative
- **ad-creative-pipeline** → Full ad creation workflow (research → creative brief → ads)
- **meta-image-ad-generator** → Facebook/Instagram image ad copy and concepts
- **meta-video-ads** → Video ad scripts for Meta platforms
- **unicorn-ad-creative-engine** → Premium ad creative system (from Max's framework)

### Landing Pages & Funnels
- **advertorial-architect** → Long-form advertorials and native content
- **listicle-architect** → Listicle-style landing pages
- **quiz-funnel-architect** → Interactive quiz funnels
- **unicorn-conversion-engine** → High-converting landing page system
- **conversion-copy-architect** → Direct response copy for any format

### Long-Form Sales
- **legendary-sales-letter** → Classic long-form sales letters
- **vsl-master-architect** → Video sales letter scripts

### SEO & Content
- **ai-seo-intelligence** → SEO-optimised content that ranks and converts

### Quality Control
- **expert-review-panel** → Multi-expert review of any content
- **qa-reviewer** → Quality assurance checks before delivery

## Standard Workflow

### MANDATORY: Conversion Mode Selection
**Before creating ANY landing page, advertorial, sales page, quiz funnel, or ad creative**, you MUST ask the user to select a conversion mode using AskUserQuestion. No exceptions. This shapes every word, claim, and tactic on the page.

#### Mode Definitions

**Whitehat / Compliant**
- Conservative, fully substantiated claims only
- Brand-forward design and messaging
- Soft CTAs ("Learn more", "See details")
- Hedged language ("may help", "designed to support")
- FDA/FTC-safe supplement language
- Social proof presented factually without amplification
- No manufactured urgency or scarcity
- Best for: established brands, regulated industries, long-term brand building

**Greyhat / Semi-Aggressive**
- Stronger benefit claims pushed to the edge of substantiation
- Direct response over branding — every element exists to convert
- Hard CTAs with urgency ("Get my discount before it's gone")
- Specific outcome language ("relief in 2 weeks" vs "may support comfort")
- Aggressive curiosity gaps, pattern interrupts, and open loops
- Amplified social proof (lead with strongest results, imply they're typical)
- Manufactured urgency: limited stock, expiring discounts, countdown timers
- Stronger fear-of-missing-out and loss aversion framing
- Objection crushing over objection handling
- Testimonials positioned as expected outcomes, not outliers
- Advertorials styled to feel indistinguishable from editorial content
- Best for: cold traffic, paid ads, competitive supplement/DTC markets, maximum conversion

### New Campaign
1. **Ask Conversion Mode** (whitehat or greyhat) — MANDATORY
2. Check for `campaign_brief.md` → read if exists
3. If no brief: use **dr-market-research** to gather intelligence
4. Use **persona-architect** to define target audience
5. Use **brand-style-extractor** or **brand-extraction** for voice
6. Select appropriate content skill based on deliverable
7. Run **qa-reviewer** before final delivery

### Quick Content Request
1. **Ask Conversion Mode** (whitehat or greyhat) — MANDATORY
2. Check for `campaign_brief.md`
3. Load relevant skill
4. Generate content
5. QA check

## Output Standards
- Save all outputs to `/output/` directory
- Use descriptive filenames: `[type]-[client]-[version].md`
- Include performance notes with each deliverable
- Flag any assumptions made

## Response Format
- Lead with the deliverable, not explanation
- Use headers to organise long outputs
- Include "Creative Rationale" section for ads/copy
- Flag split-test variants clearly

## Quality Bars
- **Headlines**: Must be specific, benefit-led, curiosity-driven
- **Body copy**: Short sentences, active voice, one idea per paragraph
- **CTAs**: Specific action + reason to act now
- **Social proof**: Always include if available in brief
- **Risk reversal**: Include guarantee/trial language where appropriate

## File Naming Conventions
```
output/
├── research/
│   ├── market-research-[client].md
│   └── persona-[segment]-[client].md
├── ads/
│   ├── meta-image-[campaign]-v1.md
│   └── meta-video-[campaign]-v1.md
├── pages/
│   ├── advertorial-[topic]-v1.md
│   ├── listicle-[topic]-v1.md
│   └── lp-[campaign]-v1.md
└── sales/
    ├── sales-letter-[product]-v1.md
    └── vsl-[product]-v1.md
```

## Integration Notes
- Always cross-reference research with actual client data in brief
- When using multiple skills in sequence, maintain context between them
- Skills can be chained: research → persona → creative → QA
- Each skill has its own activation command listed in its SKILL.md
