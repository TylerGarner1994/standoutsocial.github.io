# QA Reviewer Skill

## Activation
Use this skill when: Final quality check before delivering content to client or launching campaigns.

**Activate with**: "QA review this", "Run quality check", "Review before delivery"

## Quick QA Checklist

### For All Content
- [ ] Does it clearly communicate what the product/service is?
- [ ] Does it clearly communicate who it's for?
- [ ] Does it have a clear call to action?
- [ ] Is it free from spelling and grammar errors?
- [ ] Is it in the correct brand voice?
- [ ] Are all claims supportable or qualified?

### For Ad Copy
- [ ] Hook is strong enough to stop the scroll?
- [ ] First line works as standalone (text often truncated)
- [ ] Headline under 40 characters (Meta)
- [ ] CTA is specific and clear
- [ ] Platform policy compliance checked
- [ ] At least 3 variants provided for testing

### For Landing Pages
- [ ] Above the fold communicates the offer without scrolling
- [ ] Primary CTA visible without scrolling
- [ ] Social proof present
- [ ] Risk reversal/guarantee present
- [ ] Mobile formatting considered
- [ ] Load speed considerations noted

### For Email
- [ ] Subject line under 50 characters
- [ ] Preview text complements subject line
- [ ] One primary CTA (not multiple competing)
- [ ] Personalisation tokens present where appropriate
- [ ] Unsubscribe mechanism noted
- [ ] Mobile preview considered

### For Sales/VSL Copy
- [ ] Problem is established within first 10% of copy
- [ ] Mechanism named and explained
- [ ] Proof stack present (minimum 3 types of proof)
- [ ] Offer clearly presented with value stack
- [ ] Guarantee present and specific
- [ ] P.S. present (for long-form)

## Issue Severity Levels

**Critical** (must fix before delivery):
- Missing CTA
- Compliance issues
- Factually incorrect claims
- Severe brand voice mismatch
- Significant persuasion gap

**Major** (should fix before delivery):
- Weak headline/hook
- Missing social proof
- Unclear offer
- Missing objection handling

**Minor** (improve if time allows):
- Could be more specific
- Additional variant would improve testing
- Minor voice inconsistency

## QA Report Format

```markdown
# QA Review: [Content Name]
*Date: [Date]*
*Content type: [Type]*

## Verdict: [APPROVED / APPROVED WITH CHANGES / REVISE]

## Issues Found

### Critical
- [Issue description] — [Location in content] — [Recommended fix]

### Major
- [Issue description] — [Location] — [Recommended fix]

### Minor
- [Issue description] — [Suggested improvement]

## What's Working Well
- [Specific strength 1]
- [Specific strength 2]
- [Specific strength 3]

## Ready For Delivery: [YES / NO / YES WITH CHANGES]
```

## Integration Notes
- Run this as the final step before every client delivery
- Use after expert-review-panel for comprehensive quality control
- Document all changes made after QA for version control
