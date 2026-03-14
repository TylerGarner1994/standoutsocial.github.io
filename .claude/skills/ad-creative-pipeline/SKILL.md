# Ad Creative Pipeline Skill

## Activation
Use this skill when: Creating a complete ad campaign from scratch, need structured workflow for multiple ad formats, client wants research-backed creatives.

**Activate with**: "Use the ad creative pipeline" or "Run the full ad creation process"

## What This Skill Does
Orchestrates the complete ad creation process:
1. Market research and competitor analysis
2. Audience persona development
3. Creative brief creation
4. Multi-format ad generation
5. Copy refinement and variations
6. QA review

## Pipeline Stages

### Stage 1: Research Foundation
```
Inputs needed:
- Client/product name
- URL or product description
- Target market (if known)
- Competitor names (if known)
- Budget/platform context

Outputs:
- Market intelligence report
- Competitor ad analysis
- Customer psychology insights
- Key pain points and desires
```

### Stage 2: Audience Definition
```
Inputs: Research from Stage 1

Outputs:
- 2-3 detailed customer personas
- Primary/secondary/tertiary audience segments
- Psychographic profiles
- Language patterns and objections
```

### Stage 3: Creative Brief
```
Inputs: Research + Personas

Outputs:
- Campaign positioning statement
- 5-7 core message angles
- Proof points and claims
- Visual direction notes
- Tone and voice guidelines
```

### Stage 4: Ad Creation
```
Formats to produce (based on brief):
- Facebook/Instagram image ads (3-5 variants)
- Video ad scripts (2-3 variants)
- Carousel concepts (1-2 variants)
- Story/Reel concepts (1-2 variants)
```

### Stage 5: Refinement
```
For each ad:
- Primary headline variants (3 options)
- Body copy variants (2-3 lengths)
- CTA variants (3 options)
- Hook variants for video (3 options)
```

### Stage 6: QA Review
```
Checks:
- Platform policy compliance
- Brand voice consistency
- Claim verification flags
- Conversion optimisation
- A/B test structure
```

## Quick Pipeline (Time-Pressed)
When client needs fast turnaround:
1. Skip deep research → use provided brief
2. Skip persona development → use provided segments
3. Jump to Stage 3 (Creative Brief) with assumptions
4. Produce 3 variants per format instead of 5
5. Light QA check

## Output Format
```markdown
# Campaign: [Client] — [Campaign Name]

## Research Summary
[Key insights in bullet points]

## Target Audience
[Primary persona summary]

## Message Hierarchy
1. Primary: [Main message]
2. Secondary: [Supporting message]
3. Tertiary: [Objection handler]

## Creative Assets

### Image Ads
**Ad 1 — [Angle Name]**
Headline: 
Body: 
CTA: 

[Repeat for each ad]

### Video Scripts
**Script 1 — [Angle Name]**
Hook (0-3s): 
Problem (3-8s): 
Solution (8-20s): 
Proof (20-30s): 
CTA (30-35s): 

[Repeat for each script]

## Testing Recommendations
[Priority test recommendations]
```

## Integration With Other Skills
- **Research phase**: Use dr-market-research skill
- **Persona phase**: Use persona-architect skill
- **Image ads**: Use meta-image-ad-generator skill
- **Video ads**: Use meta-video-ads skill
- **Long-form**: Use advertorial-architect or listicle-architect
- **QA phase**: Use qa-reviewer skill

## Performance Benchmarks
Aim for:
- CTR: >2% (cold audience), >4% (warm audience)
- Hook rate: >25% for video
- CPM efficiency: Within 20% of account average
- Conversion rate: Minimum 2x industry average

## Notes
- Always produce minimum 3 creative variants per format
- Document the psychological principle behind each angle
- Flag any claims that need verification before running
- Include suggested test priority order
